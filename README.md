# :drop_of_blood::syringe: Stroke Analysis and Predictions :syringe::drop_of_blood:

## :microscope::memo: EDA + CLASSIFICATION MODELING + VIZ :memo::microscope:

![Banner](https://github.com/yuunam97/stroke-analysis/blob/main/images/stroke-banner.png?raw=true)

### Description: 
This analysis explores a stroke dataset with 5,110 entries, emphasizing factors influencing stroke occurrence. It addresses class imbalance and uncovers insights like age, hypertension, heart disease, marital status, and employment type significantly affecting stroke risk. EDA and Prediction on stroke was achieved based on these factors.

The dataset I used is [here](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) from Kaggle. 

### Tools used for EDA & Predictive Modeling:
- Python (3.12.0)
- Plotly (5.18.0)
- Sklearn (1.3.1)
- Matplotlib (3.8.0)
- imblearn (0.0)
- Jupyter Notebook

### Models used for predictive modeling:
- Logistic Regression (Main)
- Random Forest Classifier
- Decision Tree Classifier
- SVM

### The goal of this project:
- EDA, and data visualization on the stroke dataset. 
- Predictive modeling (Numerical and Categorical Analysis) in align with correlation analysis on the factors towards stroke.
- Identify stroke patterns/trends.
- Highlight key factors contributing to the stroke.
- Inform preventive measures for the development of targeted preventive measures, leveraging insights into demographic and health-related factors associated with stroke occurrence.

### What I've learned:
- EDA using Python.
- Classification problem with predictive modeling using Logistic Regression and Random Forest Classifier. 
- Effective data visualization using pie charts, kdeplots, bar charts, etc.
- Class imbalance mitigation using SMOTE (Synthetic Minority Oversampling Technique). 


- **Correlation Map of Features vs Stroke**

![correlation](https://github.com/yuunam97/stroke-analysis/blob/main/images/1_correlation.png?raw=true)

![features](https://github.com/yuunam97/stroke-analysis/blob/main/images/1-features.png?raw=true)

- **Distribution of Numerical Data:**

![correlation](https://github.com/yuunam97/stroke-analysis/blob/main/images/3-numerical-data.png?raw=true)

- **Distribution of Categorical Data:**

![correlation](https://github.com/yuunam97/stroke-analysis/blob/main/images/5-categorical-data.png?raw=true)

- Identified a prominent correlation between age and stroke risk; as age increases, the likelihood of stroke also rises.

![age](https://github.com/yuunam97/stroke-analysis/blob/main/images/1-features.png?raw=true)

- Marginal differences observed in stroke likelihood between smokers and non-smokers. Similar likelihood of stroke between individuals living in urban and rural areas.

![smoke](https://github.com/yuunam97/stroke-analysis/blob/main/images/8-smoke.png?raw=true)

![areas](https://github.com/yuunam97/stroke-analysis/blob/main/images/8-residential.png?raw=true)

- Marriage status showed a significant impact, with those married having almost five times the likelihood of stroke. :satisfied:

![marriage](https://github.com/yuunam97/stroke-analysis/blob/main/images/8-marriage.png?raw=true)

- Private and government employment types had similar stroke chances, while self-employed individuals faced a higher risk.

![jobs](https://github.com/yuunam97/stroke-analysis/blob/main/images/8-work-type.png?raw=true)

- Logistic Regression performed the best when predicting stroke. This performance was followed by Random Forest Classifier. 

![five-models](https://github.com/yuunam97/stroke-analysis/blob/main/images/9-five-model-tuned.png?raw=true)

![roc-curve](https://github.com/yuunam97/stroke-analysis/blob/main/images/12-roc-curve.png?raw=true)

### Credits
1. [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
2. Inspirations from [Josh](https://www.kaggle.com/code/joshuaswords/predicting-a-stroke-shap-lime-explainer-eli5).
3. EDA on Stroke by [Zhe Yeap](https://towardsdatascience.com/step-by-step-exploratory-data-analysis-on-stroke-dataset-840aefea8739)