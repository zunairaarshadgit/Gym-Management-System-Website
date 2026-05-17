
# Gym Management System (Flask) — Lab 6

## Project Overview

This project is a Gym Management System developed using Flask (Python) as part of Lab 6. The system is designed to manage basic gym-related operations such as user registration, member management, and navigation between multiple pages using Flask routing.

The project demonstrates core concepts of web development including backend routing, template rendering, and frontend integration using HTML, CSS, and Bootstrap.

---

## Objectives

* To develop a basic web-based Gym Management System
* To understand Flask routing and template rendering
* To implement form handling using Flask
* To design a responsive frontend using Bootstrap
* To simulate basic CRUD-style structure (without full database complexity if not implemented)

---

## Features

### Pages Included

* Home Page (Dashboard view)
* About Page (Gym information)
* Services Page (Gym services)
* Membership / Registration Page
* Contact Page
* Login Page (if included)

---

### Functionalities

* Multi-page navigation using Flask routes
* User registration form (basic/demo or database-based depending on implementation)
* Login system (basic authentication logic if implemented)
* Form submission handling using POST method
* Redirect system after successful actions
* Responsive UI using Bootstrap

---

## Technologies Used

### Backend

* Python 3
* Flask Framework

### Frontend

* HTML5
* CSS3
* Bootstrap 5

---

## Project Structure

```text id="gym_structure"
Gym-Management-System/
│
├── app.py
│
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── services.html
│   ├── contact.html
│   ├── login.html
│   ├── register.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── images/
│
└── README.md
```

---

## Installation Instructions

### 1. Install Python

Ensure Python 3.x is installed.

```bash id="py_check"
python --version
```

---

### 2. Create Virtual Environment (Optional)

```bash id="venv_create"
python -m venv venv
```

Activate environment:

Windows:

```bash id="venv_win"
venv\Scripts\activate
```

Mac/Linux:

```bash id="venv_linux"
source venv/bin/activate
```

---

### 3. Install Flask

```bash id="install_flask"
pip install flask
```

---

### 4. Run the Project

```bash id="run_app"
python app.py
```

---

### 5. Open in Browser

```text id="browser"
http://127.0.0.1:5000/
```

---

## How the Project Works

* Flask handles all routing using `@app.route`
* HTML pages are stored inside the `templates` folder
* Static files are stored inside the `static` folder
* Forms use POST method for data submission
* Data handling is either temporary or database-based depending on implementation
* Navigation is managed using Flask `url_for`

---

## Limitations

* No advanced authentication system (if not implemented)
* No full database integration (if not added)
* Data may be temporary depending on implementation
* No admin panel unless separately implemented

---

## Future Improvements

* Integration with SQLite or MySQL database
* Secure login system with password hashing
* Admin dashboard for managing members
* Attendance tracking system
* Payment management system
* Role-based authentication (Admin/User)

---

## Conclusion

This Gym Management System demonstrates the fundamental concepts of Flask web development including routing, form handling, and template rendering. It provides a foundational understanding of how backend and frontend integration works in a web application.

---

## License

This project is developed for educational purposes only.

---

