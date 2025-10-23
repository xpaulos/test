# My Flask App

This is a simple Flask web application designed to demonstrate the structure and functionality of a Flask project.

## Project Structure

```
my-flask-app
├── src
│   ├── app
│   │   ├── __init__.py
│   │   ├── routes.py
│   │   ├── models.py
│   │   ├── forms.py
│   │   ├── templates
│   │   │   ├── base.html
│   │   │   └── index.html
│   │   └── static
│   │       ├── css
│   │       │   └── styles.css
│   │       └── js
│   │           └── main.js
│   └── config.py
├── tests
│   └── test_app.py
├── requirements.txt
├── .gitignore
├── Dockerfile
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd my-flask-app
   ```

2. **Create a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   flask run
   ```

## Usage

Once the application is running, you can access it at `http://127.0.0.1:5000/`. The main page will display the content defined in `index.html`.

## Testing

To run the tests, ensure you are in the virtual environment and execute:
```bash
pytest tests/test_app.py
```

## License

This project is licensed under the MIT License.