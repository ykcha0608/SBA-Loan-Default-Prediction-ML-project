# SBA-Loan-Default-Prediction-ML-project

## Summary

Project 2 aims to provide students with practical experience in Data Science concepts, focusing on classification model training, feature engineering, and model interpretation. The project facilitates learning through structured tasks and requirements.

## Techniques Used

### Data Preparation:
- **Data Loading:** Excludes the "index" column for training.
- **Data Cleaning:** 
  - Encoding to replace missing values.
  - Rectifying incorrect feature values.
  - Converting numerical variables presented as strings to numerical values.
  - Encoding categorical variables.
- **Dataset Splitting:** Divides the dataset into Train/Test/Validation sets.

### Feature Engineering:
- **Engineered Features:** Introduces at least 10 new engineered features.
- **Techniques:**
  - Utilizes techniques from GLM lectures and Module-3 hands-on sessions.

### Model Training and Tuning:
- **Models:**
  - GBM (H2O).
  - LightGBM.
- **Hyper-parameter Tuning:**
  - Searches a space of at least 150 combinations or trials.
  - Performs cross-validation if applicable.

### Model Evaluation:
- **Metrics:**
  - Confusion matrix for best F1 score.
  - Global feature importance using Shapley values and permutation feature importance.
  - Individual observation analysis using Shapley values for specific scenarios.

### Scoring Function:
- **Single Function:** Submits a single scoring function for either GBM or LightGBM model.
- **Activities:**
  - Data transformation.
  - Scoring.
  - Results return.

### Model Interpretation:
- **Visualization:**
  - Shapley summary graph.
  - Shapley feature interaction graphs.
  - Single records Shapley graphs with explanations.
- **Discussion:**
  - Identifies strong/weak points of the model.
  - Discusses scenarios requiring overwriting model predictions.

## Conclusion

Project 2 offers a hands-on experience in various Data Science techniques, enhancing students' skills in data manipulation, model building, and interpretation. The structured tasks and requirements ensure a thorough understanding and application of these concepts.
