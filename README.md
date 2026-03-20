![Static Badge](https://img.shields.io/badge/python-3.11-blue)
![Static Badge](https://img.shields.io/badge/django%20version-%5E4.1-green)

# mini-eCommerce
mini-eCommerce is a virtual online shop built using the Django framework.

![home](https://github.com/user-attachments/assets/a6680303-020c-45e2-a721-22f095f932ce)

## API Documentation
To learn how to use the API, please refer to the [mini-eCommerce API documentation](https://app.swaggerhub.com/apis-docs/Yanpin/mini-ecommerce-api/1.0.0).

## Tech Stack
- Django
- Django REST framework
- Bootstrap
- MySQL

# Installation
### Prerequisites
Please ensure that you have the following installed on your local machine:
- Python 3.11.8
- MySQL

## 1. Clone this repository
```
git clone https://github.com/yanpin0524/mini_ecommerce_app.git
```
Navigate to the project folder
```
cd "project path"
```

## 2. Create .env file based on .env.example
> [.env.example](https://github.com/yanpin0524/mini_ecommerce_app/blob/main/.env.example)

## 3. Install Python packages
#### Using pip
```
pip install -r requirements.txt
```
#### Using Poetry
```
poetry install
```

## 4. Migrate the Database
```
python manage.py migrate
```

## 5. [Optional] Create some random seed data on your server
> --number=${number of seed data}
```
python manage.py seed shop --number=10
```

## 6. Run the Django server on your machine
```
python manage.py runserver
```


# Quickly Install with Docker
please make sure you already have Docker on your local machine

### 1. Clone this repository
```
git clone https://github.com/yanpin0524/mini_ecommerce_app.git
```
Navigate to the project folder
```
cd "project path"
```
### 2. Build the app using Docker Compose
```
docker-compose build
```
### 3. Start the server using Docker Compose
```
docker-compose up -d
```
### 4. Check the server on localhost
Open your browser and go to:
```
http://localhost:8000/products/
```
### 5. Stop the server
To stop the server, use the following command:
```
docker-compose down
```



# Author
[@yanpinchouli](https://github.com/yanpinchouli)
