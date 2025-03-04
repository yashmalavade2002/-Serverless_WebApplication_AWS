# ☁️🚀 Serverless Web Application on AWS ☁️  

This project is a serverless web application using **AWS API Gateway, AWS Lambda, and Amazon DynamoDB** to handle **GET and POST requests**.  

## ☁️🏗️ Architecture  
1. **☁️🛡️ API Gateway**: Exposes RESTful endpoints to handle HTTP requests.  
2. **☁️⚡ AWS Lambda**: Executes backend logic for processing requests.  
3. **☁️📦 Amazon DynamoDB**: Stores and retrieves application data.  
4. **☁️🔐 IAM (Identity and Access Management)**: Manages permissions and secures AWS resources.  

## ☁️✨ Features  
- ✅ **GET Request**: Fetches data from DynamoDB.  
- 📝 **POST Request**: Inserts new data into DynamoDB.  
- 🔐 **IAM Roles**: Controls access between AWS services securely.  
- ☁️ **Serverless**: No need to manage servers, leveraging AWS Lambda.  

## ☁️🔧 Prerequisites  
- 🏢 AWS account  
- 🖥️ AWS CLI installed and configured  
- 📌 Node.js and npm installed (for deploying with Serverless Framework)  
- ⚙️ Serverless Framework (Optional, but recommended)  

## ☁️🚀 Setup and Deployment  

### 1️⃣ Clone the Repository  
# ☁️🚀 Serverless Web Application on AWS ☁️

This project is a serverless web application using AWS API Gateway, AWS Lambda, and Amazon DynamoDB to handle GET and POST requests.

## ☁️🏗️ Architecture

1. **☁️🛡️ API Gateway**: Exposes RESTful endpoints to handle HTTP requests.
2. **☁️⚡ AWS Lambda**: Executes backend logic for processing requests.
3. **☁️📦 Amazon DynamoDB**: Stores and retrieves application data.

## ☁️✨ Features

- ✅ **GET Request**: Fetches data from DynamoDB.
- 📝 **POST Request**: Inserts new data into DynamoDB.
- ☁️ **Serverless**: No need to manage servers, leveraging AWS Lambda.

## ☁️🔧 Prerequisites

- 🏢 AWS account
- 🖥️ AWS CLI installed and configured
- 📌 Node.js and npm installed (for deploying with Serverless Framework)
- ⚙️ Serverless Framework (Optional, but recommended)

## ☁️🚀 Setup and Deployment

### 1️⃣ Clone the Repository

```sh
 git clone <repository-url>
 cd serverless-webapp
```

### 2️⃣ Install Dependencies

```sh
 npm install -g serverless
```

### 3️⃣ Configure AWS Credentials

```sh
 aws configure
```

### 4️⃣ Deploy the Application

```sh
 serverless deploy
```

## ☁️🌐 API Endpoints

### 1️⃣ POST - Create Item

```sh
curl -X POST https://<api-gateway-url>/items \
    -H "Content-Type: application/json" \
    -d '{"id": "1", "name": "Sample Item"}'
```

### 2️⃣ GET - Retrieve Item

```sh
curl -X GET https://<api-gateway-url>/items/1
```

## ☁️📸 Architecture Diagram  
![Architecture Diagram](path/to/architecture-diagram.png) 
