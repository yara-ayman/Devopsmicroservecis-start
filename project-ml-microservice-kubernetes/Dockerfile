FROM python:3.7.3-stretch


WORKDIR /app

COPY . /app/


RUN pip install --upgrade pip &&\
	pip install -r requirements.txt
	
Expose 80

CMD ["python", "app.py"]

## Step 1:
# Create a working directory

## Step 2:
# Copy source code to working directory

## Step 3:
# Install packages from requirements.txt
# hadolint ignore=DL3013

## Step 4:
# Expose port 80

## Step 5:
# Run app.py at container launch

