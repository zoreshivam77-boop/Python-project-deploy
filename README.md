# Python Application – Deployment

This project is a simple **Python application** deployed using and a EC@ instace, python3 and pyhton package manager pip .The application contains two Flask routes and can be run locally using Flask or in a production-like environment using **Gunicorn**.

## Technologies Used

- **Python** – Programming language
- **Gunicorn** – Python WSGI server
- **Git & GitHub** – Source code management


## Application Routes

### `/`

Displays a message confirming that the Python application was successfully deployed through Jenkins and the GitHub webhook.Provided with screenshot of brower of that deployed project.

###

## Project Structure

```text
.
├── app.py
├── requirements.txt
└── README.md
```

## Requirements

The required Python packages are listed in `requirements.txt`.

Install them using:

```bash
pip install -r requirements.txt
```

## Run the Application Locally

Start the Flask application:

```bash
python3 app.py
```

The application runs on:

```text
http://localhost:5000
```

## Run Using Gunicorn

Gunicorn can be used to run the application:

```bash
gunicorn --bind 0.0.0.0:5000 app:app
```
_name__)
```
