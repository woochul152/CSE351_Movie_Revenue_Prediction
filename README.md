# CSE351_Movie_Revenue_Prediction

📌 Overview

Predicts movie revenue using regression models on the TMDB dataset.
Compares baseline and advanced models to evaluate the impact of feature engineering.

⸻

🚀 Models
	•	Baseline (Simple Linear Regression)
	•	Uses log(Budget) only
	•	Multiple Linear Regression
	•	Uses multiple features (popularity, vote count, crew size, etc.)
	•	Polynomial Regression
	•	Captures nonlinear relationships (prone to overfitting)

⸻

📈 Results
	•	Baseline RSE: ~1.47
	•	Multiple Regression RSE: ~1.13 (-23%)
	•	Polynomial: Overfitting observed

👉 Multiple regression achieved the best performance.

⸻

🧠 Key Contributions
	•	Feature engineering from structured and categorical data
	•	Log transformation to reduce skewness
	•	Model comparison using RSE
	•	Time-based evaluation (pre/post 2010 distribution shift)

⸻

📉 Note

Visualization is shown against log(Budget) for interpretability and comparison with the baseline model.

⸻

🛠️ Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib  

