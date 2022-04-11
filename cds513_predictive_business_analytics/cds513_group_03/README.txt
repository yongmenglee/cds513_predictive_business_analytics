# ============================================================
# CDS513: GROUP PROJECT (by: Group 3)
# ============================================================

# ------------------------------------------------------------
# Submission Files
# ------------------------------------------------------------

The submission files are organized as follows:

- CDS513_Group3_FINAL_REPORT.pdf: The final report for the project.

- CDS513_Group3_POSTER.pdf: The poster used for presentation.

- RapidMiner folder: RapidMiner data and process to implement MBA and RS.
  - Market_Basket_Analysis folder: 
    - data: transaction-item utility matrix
    - process: MBA process
  - Recommender_System folder: 
    - data: user preference data (training and test set)
    - process: 4 processes, including 00_Generate_RM_Object, 01_User_to_User_CF, 02_Item_to_Item_CF, and 03_Bayesian_CF
    - output: 
      - CSV files: list of recommendations generated using different CFRS
      - IOO files: performance of different CFRS (opened with RapidMiner)

- Python folder: 3 notebooks (with the corresponding HTML files) containing Python codes used for this project.
  - Data_Preprocessing_MBA.*: Data preprocessing steps to generate transaction-item utility matrix for MBA. 
  - Data_Preprocessing_RS.*: Data preprocessing steps to generate user preference data used for RS.
  - Time_Series_Forecasting.*: Complete process for time series analysis and forecasting, including data preprocessing steps to generate daily sales data for selected category and building time series models including ARIMA and machine learning model.


# ------------------------------------------------------------
# Original Dataset - from Kaggle
# ------------------------------------------------------------

The original dataset can be retrieved from the links below:

- Purchase data - 284.81 MB: https://www.kaggle.com/mkechinov/ecommerce-purchase-history-from-electronics-store
- User behaviour data (Oct 2019) - 5.28 GB: https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store?select=2019-Oct.csv


Thank you and stay healthy!


Best regards,
Group 3

