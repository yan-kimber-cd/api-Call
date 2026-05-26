API CALL

Author: Kimber C. Yanquiling 

Project Title

API Call

Project Description

This project is a simple Laravel API application created for practicing API calls using routes and controllers. It demonstrates the basic CRUD operations such as retrieving, inserting, updating, and deleting student records stored in the database. The project also shows how API endpoints can be tested using Postman.


---

Installation and Setup

1. Download or Clone the Project

Download or clone the repository, then open the project folder using [Visual Studio Code](https://code.visualstudio.com?utm_source=chatgpt.com).

2. Install Required Applications

Install [Laravel Herd](https://herd.laravel.com?utm_source=chatgpt.com) and the SQLite Viewer extension in VS Code to manage and view the SQLite database.

3. Install Project Dependencies

Open the terminal inside the project directory and run:

composer install

4. Configure the Environment File

Copy the .env.example file and rename it to .env. After that, configure the database connection settings.

5. Generate the Application Key

Run the following command:

php artisan key:generate

6. Run Database Migration

Create the database tables by running:

php artisan migrate

7. Start the Development Server

Run the Laravel server using:

php artisan serve

8. Access the API

Open the following URL in your browser to display all student records:

http://127.0.0.1:8000/api/students


---

API Testing Using Postman

Open [Postman](https://www.postman.com?) and create a collection for the project.

Retrieve All Student Records

GET http://127.0.0.1:8000/api/students

This endpoint displays all student data stored in the database.

Retrieve a Specific Student Record

GET http://127.0.0.1:8000/api/students/5

Replace 5 with the desired student ID to retrieve a specific student record.


---

Demo Tutorial

[Google Drive Demo Tutorial](https://drive.google.com/file/d/1Ap81uchVSoy_sGLh_621gDIfb2yw2DH4/view?usp=drivesdk)

The demo tutorial shows how to test Laravel API endpoints using Postman and explains how the API requests work.