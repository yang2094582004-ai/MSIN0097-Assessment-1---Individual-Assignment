# King County House Price Prediction (MSIN0097 Coursework)

## Description

This project is a university machine learning coursework submission focused on predicting residential house prices in King County using supervised regression models.

The complete predictive analytics workflow — including exploratory data analysis (EDA), preprocessing, model development, evaluation, and refinement — is implemented in the notebook:

**PA.ipynb**

The objective is to build and compare multiple regression models and select the best-performing model based on Root Mean Squared Error (RMSE).

---

## Project Files

- **PA.ipynb** – Main notebook containing data exploration, preprocessing, model training, evaluation, and model comparison  
- **kc_house_data.csv** – King County Housing dataset used for training and testing  
- **requirements.txt** – Python dependencies required to run the project  
- **README.md** – Project documentation and execution instructions  

---

## Dataset

The project uses the **King County Housing dataset**, which contains residential property information such as:

- Living area (sqft)
- Number of bedrooms and bathrooms
- Grade and condition
- Location features
- Sale price

**Prediction task:** Regression (house price prediction)  
**Target variable:** log1p(price)  
**Evaluation metric:** Root Mean Squared Error (RMSE)

---

## Models Implemented

The following models were implemented and compared:

- Dummy Regressor (baseline)
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor (final selected model)

---

## Environment Requirements

Python version:

Install required dependencies:

```bash
pip install -r requirements.txt

## How to Run

Step 1: Navigate to the project folder

Step 2: Install dependencies

pip install -r requirements.txt

Step 3: Open the notebook

jupyter notebook PA.ipynb

Step 4: Run all cells from top to bottom

The notebook will perform data preprocessing, model training, evaluation, and output model performance results.

## Data Access

The dataset file kc_house_data.csv is included in this repository.

No additional download is required. The notebook reads the dataset directly from the project folder.