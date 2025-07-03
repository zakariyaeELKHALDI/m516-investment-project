# 💸 M516 Investment Project – Micro-Investment Strategy Simulation (Bitcoin)

[❗❗❗❗❗Presentation Video Link❗❗❗❗❗][❗ https://drive.google.com/file/d/1vxG5Y5h5i0d0MNMSJhMDftBY5KXx16vo/view?usp=sharing ❗]

This repository contains my final project for the **M516 Business Project in Big Data & AI** at Gisma University of Applied Sciences.

The project simulates a realistic micro-investment strategy using historical Bitcoin data, predictive modeling, and a rule-based simulation engine. It is designed as a modular, reproducible analysis pipeline in Python, built and documented entirely in a Jupyter Notebook.

---

## 📘 Notebook Report

> The entire analysis — from setup to conclusion — is documented in a single Jupyter Notebook.

🔍 It includes:

- Environment setup and dependencies
- Data download and preprocessing (via `yfinance`)
- Exploratory Data Analysis (EDA)
- Price trend visualization with Plotly
- Return and volatility analysis
- Predictive modeling (ARIMA, etc.)
- Investment strategy simulation
- Evaluation of results and performance metrics
- Key takeaways and possible improvements

📎 **Interactive HTML Version**  
👉 [Download and view the full interactive notebook with Plotly charts](https://github.com/zakariyaeELKHALDI/m516-investment-project/raw/main/report.html)

📝 **Jupyter Notebook (Static Preview)**  
[`report.ipynb`](./report.ipynb)

---

## 🧰 Setup Instructions

The project was developed in a clean virtual environment using Python 3.12.

To recreate the environment:

```bash
git clone https://github.com/zakariyaeELKHALDI/m516-investment-project.git
cd m516-investment-project
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
jupyter notebook
```

🧪 Requirements
All required packages are listed in requirements.txt.
Major dependencies include:

`pandas`

`numpy`

`yfinance`

`plotly`

`statsmodels`

`scikit-learn`

`matplotlib`

`kaleido` (for static Plotly image export, if needed)

🎥 Project Demo Video
📹 A short 3–5 min demo video showcasing the project pipeline and results will be added here:
[https://drive.google.com/file/d/1vxG5Y5h5i0d0MNMSJhMDftBY5KXx16vo/view?usp=sharing]

👤 Author
Zakariyae EL KHALDI
MSc Data Science – Gisma University of Applied Sciences
GitHub Profile

📌 Notes

- The notebook is fully self-contained and explains every step in great detail, including the environment setup.

- All plots, strategies, and decisions are thoroughly documented for transparency and reproducibility.

- Interactive charts are only visible in the .html version due to GitHub limitations on rendering Plotly.
