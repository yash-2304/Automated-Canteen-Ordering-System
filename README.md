# 🍽️ Automated Canteen Ordering System

This project is a simple web-based automated canteen ordering system built with **Python (Flask)** for the backend and **HTML/CSS/JavaScript** for the frontend. Users can submit food orders through a clean web interface, and all orders are stored in a local SQLite database.

## 🔧 Tech Stack

- **Backend**: Python, Flask, SQLite
- **Frontend**: HTML, CSS, JavaScript
- **Templating**: Jinja2 (Flask built-in)

## ✨ Features

- Submit food orders with item and quantity
- Display all placed orders on the same page
- Backend data stored in SQLite for persistence
- Alert-based confirmation for user feedback

## 📁 Project Structure

```
📦canteen-ordering-system
├── canteen_ordering_system.py      # Flask backend
├── templates
│   └── index.html                  # HTML frontend
└── README.md
```

## ▶️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/canteen-ordering-system.git
cd canteen-ordering-system
```

### 2. Install dependencies
```bash
pip install flask flask_sqlalchemy
```

### 3. Run the application
```bash
python canteen_ordering_system.py
```

### 4. Open in browser
Go to `http://127.0.0.1:5001`

## 📝 Example Usage

- Enter customer name
- Select item (e.g. Pizza, Burger, Cold Coffee)
- Choose quantity
- Click "Place Order" to submit

## 🚀 Future Enhancements

- Admin dashboard for managing orders
- API endpoint integration for Android app
- Live order tracking with AJAX
- User authentication

## 📄 License

This project is licensed under the MIT License.

---

Made with ❤️ using Flask and a pinch of frontend magic!
