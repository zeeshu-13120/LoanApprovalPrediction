# 🏦 Loan Approval Prediction Project

This project aims to build a machine learning model to predict whether a loan application will be approved based on various applicant and financial features. The focus lies on tackling imbalanced data and evaluating performance using key classification metrics like **precision**, **recall**, and **F1-score**.

---

## 📌 Project Overview

The workflow followed a standard ML pipeline:

- **Data Acquisition & Preprocessing**:  
  Loading and cleaning the dataset, handling anomalies, and encoding categorical features.

- **Model Training & Evaluation**:  
  Training and comparing multiple classification algorithms:  
  `Decision Tree`, `Random Forest`, and `Logistic Regression`.

- **Imbalance Handling**:  
  Applying **SMOTE** (Synthetic Minority Over-sampling Technique) to mitigate class imbalance.

- **Performance Analysis**:  
  Emphasizing metrics like **precision**, **recall**, and **F1-score**—especially for the minority class.

- **Model Optimization**:  
  Performing **hyperparameter tuning** using `RandomizedSearchCV`.

- **Final Model Selection**:  
  Choosing the most robust and generalizable model for deployment.

---

## 🧰 Technologies Used

- **Python 3.12.10**
- **Jupyter Notebook**
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical computations
- **Scikit-learn** – ML models, preprocessing, and model evaluation
- **imbalanced-learn** – Handling imbalanced datasets via SMOTE
- **Matplotlib** – Visualizations
- **Seaborn** – Statistical plotting

---

## ⚙️ Installation

To run this project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/zeeshu-13120/Loan-Approval-Prediction.git
cd Loan-Approval-Prediction
```

**Note:** If `loan_approval_dataset.csv` is not included, download it manually from:  
https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset

### 2. Set Up Virtual Environment

```bash
# Create the environment
python -m venv venv

# Activate (Windows)
.\venv\Scripts\activate

# Activate (macOS/Linux)
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch JupyterLab

```bash
jupyter-lab
```

---

## 🧪 Usage

1. Launch JupyterLab.
2. Open the `Loan_Approval_Prediction.ipynb` notebook.
3. Execute all cells from top to bottom to run the entire workflow.
4. Follow along with comments and visualizations for detailed insights.

---

## 📁 Project Structure

```
Loan-Approval-Prediction/
├── Loan_Approval_Prediction.ipynb     # Main Jupyter notebook
├── loan_approval_dataset.csv          # Dataset file
├── requirements.txt                   # Python dependencies
├── README.md                          # Project instructions and overview
└── ProjectReport_Zeeshan.pdf          # Extended project report
```

---

## 🤝 Contributing

Pull requests are welcome. For significant changes, please open an issue first to discuss what you’d like to propose.

Be sure to update tests where applicable.

---

## 📄 License

**[Unlicense](https://unlicense.org/)** – This project is free to use without restrictions.