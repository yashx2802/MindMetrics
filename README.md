# MindMetrics – AI-Powered Student Stress Prediction System

## 📌 Overview  
MindMetrics is a Machine Learning powered web application designed to predict student stress levels based on lifestyle and academic inputs.  
The system leverages a trained ML classification model integrated with a Flask web interface to provide real-time stress analysis.

This application can assist students, educators, and researchers in understanding stress patterns efficiently.

---

## 🚀 Features  

🧠 **Stress Prediction**  
Predicts student stress levels (Low / Medium / High) using a trained ML model.

📊 **Real-Time Analysis**  
Instant predictions based on user-provided inputs.

💻 **Interactive Web Interface**  
Simple and user-friendly input form.

⚡ **Fast & Lightweight**  
Runs locally with minimal setup.

---

## 🛠️ Tech Stack  

**Frontend**  
- HTML5  
- CSS3  
- JavaScript  

**Backend**  
- Python  
- Flask  

**Machine Learning**  
- Scikit-learn  
- Pickle (Serialized Model)

**Data Handling**  
- Pandas  
- NumPy

---

## 📂 Project Structure  

MindMetrics/  
├── app.py                 # Flask backend server  
├── templates/  
│   └── index.html         # Frontend UI  
├── static/  
│   ├── style.css          # Styling  
│   └── script.js          # Optional JS logic  
├── model/  
│   ├── stress_model.pkl   # Trained ML model  
│   └── label_encoder.pkl  # Label encoder  
├── dataset/  
│   └── stress_data.csv    # Dataset  
└── README.md

---

## ⚡ Getting Started  

### 1️⃣ Clone Repository  

```bash
git clone https://github.com/yashx2802/MindMetrics.git
