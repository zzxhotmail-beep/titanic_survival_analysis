# 🚢 Titanic Survival Prediction (Neural Network)

A machine learning project based on the famous Titanic - Machine Learning from Disaster competition.
The goal is to predict whether a passenger survived the Titanic disaster using structured tabular data.

## 📌 Project Overview

This project builds a neural network model using TensorFlow/Keras to predict survival outcomes based on passenger features such as:
- Socio-economic class
- Gender
- Age
- Family relations
- Ticket fare
- Embarkation port
The model achieves a public leaderboard score of 0.78229, demonstrating solid baseline performance using deep learning on tabular data.

## 📊 Dataset

- Source: Kaggle Titanic - Machine Learning from Disaster （[Dataset](https://www.kaggle.com/competitions/titanic/data)）
  - **train.csv**: labeled data (with survival outcomes)
  - **test.csv**: unlabeled data (for prediction)
  - **gender_submission.csv**: example submission format

## ⚙️ Tech Stack

- Python
- Pandas & NumPy (data processing)
- Scikit-learn (preprocessing & train/validation split)
- TensorFlow / Keras (model building)

## 🔧 Data Preprocessing

Key preprocessing steps include:
- Handling missing values:
  - Age → median
  - Fare → median
  - Embarked → mode
- Encoding categorical variables using one-hot encoding
- Feature scaling using StandardScaler

## 📈 Model Performance

- Validation Accuracy: ~82%
- Kaggle Public Score: 0.78229

## 📁 Project Structure

- **getting_started_with_titanic_go.ipynb** # Full workflow

## 🔗 Project Link

- 📘 **Kaggle Notebook (Full Analysis & Code)**:

   - [Getting Started with Titanic Go](https://www.kaggle.com/code/zzx022308/getting-started-with-titanic-go)

## 💡 Key Learnings

- Neural networks can work on tabular data, but require proper preprocessing
- Feature engineering is often more important than model complexity
- Early stopping is effective for preventing overfitting on small datasets
- Simpler models (e.g., Logistic Regression, XGBoost) can sometimes outperform neural networks on structured data

## 📬 Author - Zixuan Zhang

This project is part of my machine learning practice and portfolio.
- **LinkedIn**: [My Professional Profile](https://www.linkedin.com/in/zixuan-zhang-78ba38274)
