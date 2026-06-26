# Student-Management-System-ASP.NET-Core-MVC

A web-based Student Management System developed using **ASP.NET Core MVC** and **SQL Server**. This project demonstrates complete CRUD (Create, Read, Update, Delete) functionality using **Stored Procedures** instead of Entity Framework.

---

## Project Overview

The application allows users to:

- Add new students
- View all students
- Update student information
- Delete student records
- Store and retrieve data from SQL Server

This project was built to strengthen my understanding of ASP.NET Core MVC architecture, SQL Server, ADO.NET, and Stored Procedures.

---

## Technologies Used

- ASP.NET Core MVC
- C#
- SQL Server
- ADO.NET
- Stored Procedures
- Bootstrap 5
- Visual Studio 2022

---

## Features

- Create student records
- Display students in a responsive table
- Edit existing student details
- Delete students with confirmation
- Server-side validation using Data Annotations
- SQL Server database integration
- Navigation using MVC routing

---

## Database

### Students Table

| Column | Type |
|---------|------|
| Id | INT (Identity) |
| Name | VARCHAR(50) |
| Email | VARCHAR(50) |
| Age | INT |

---

## Stored Procedures

The project uses SQL Server Stored Procedures for all database operations.

- sp_AddStudent
- sp_GetStudents
- sp_GetStudentById
- sp_UpdateStudent
- sp_DeleteStudent

---

## Project Structure

```
StudentSPCRUD
│
├── Controllers
│     └── StudentController.cs
│
├── Models
│     └── Student.cs
│
├── Views
│     └── Student
│           ├── Index.cshtml
│           ├── Create.cshtml
│           └── Edit.cshtml
│
├── appsettings.json
└── Program.cs
```

---

## MVC Flow

```
User
   ↓
View
   ↓
Controller
   ↓
Stored Procedure
   ↓
SQL Server Database
```

---

## Learning Outcomes

Through this project, I learned:

- ASP.NET Core MVC architecture
- CRUD operations using Stored Procedures
- SQL Server database connectivity using ADO.NET
- Model Binding
- Data Validation
- Razor Views
- SQL Parameters
- Controller and View interaction
- Database design

---

## Future Improvements

- Student Search
- Pagination
- Login Authentication
- Role-based Authorization
- Responsive Dashboard
- Export to Excel/PDF

---

## Author

**Zarnab Khan**

Bachelor's in Computer Science

Learning ASP.NET Core, SQL Server, Machine Learning, and Data Science.
