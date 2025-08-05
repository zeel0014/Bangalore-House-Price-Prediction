# 🏠 Bangalore House Price Prediction Web App

This is a full-stack Machine Learning web application to predict house prices in Bangalore. It uses a regression model trained on real housing data and allows users to input area, location, number of BHKs, bathrooms etc., to get a predicted house price.

---

## 📁 Project Structure

bangalore-house-price-prediction/
│
├── client/
│ ├── app.css # Frontend CSS styling
│ ├── app.js # Frontend JS logic to handle form & API call
│ └── app.html # Main HTML frontend
│
├── model/
│ ├── bengaluru_house_prices.csv # Original raw dataset
│ ├── my_data.csv # Cleaned/processed dataset (optional)
│ └── bhp.ipynb # Jupyter notebook with data cleaning and model training
│
├── server/
│ ├── artifacts/
│ │ ├── banglore_home_prices_model.pickle # Trained ML model (pickle file)
│ │ └── columns.json # All columns used in training (esp. locations)
│ ├── server.py # Main backend server file (Flask)
│ └── util.py # Utilities: load model, predict price


---

## 🚀 Features

- Predict Bangalore house prices based on:
  - Area (sqft)
  - BHK (bedrooms)
  - Bathrooms
  - Location
- Clean frontend UI built with HTML/CSS/JS
- API-based backend using Flask
- Reusable trained ML model with pickle

---

## 📦 Tech Stack

- Python 🐍
- Pandas, Numpy
- Scikit-learn (Linear Regression)
- Flask
- JavaScript, HTML5, CSS3

---

## 📊 Dataset Info

- Source: Kaggle / Open Real Estate Dataset
- Includes features like `location`, `area (sqft)`, `bathrooms`, `BHK`, `price`
- Model trained using Linear Regression with basic outlier removal & encoding

---
