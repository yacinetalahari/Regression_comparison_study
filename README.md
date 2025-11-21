# 📊 Regression Model Comparison Study

Hey there! Welcome to my machine learning project where I explore different regression techniques—from simple linear models to neural networks—and see how they perform on various types of data.

## What's This All About?

I built this project to understand:
- How different regression models behave with clean vs noisy data
- When to use regularization (Ridge, Lasso, ElasticNet)
- Whether neural networks are worth the extra complexity for regression tasks
- How techniques like early stopping can save time and prevent overfitting

## 🎯 What I Implemented

### The Models
- **Linear Regression** - The classic, straightforward approach
- **Polynomial Regression** - For when relationships aren't straight lines
- **Ridge Regression** - Tames wild coefficients with L2 regularization
- **Lasso Regression** - Automatically selects features with L1 regularization  
- **ElasticNet** - Gets the best of both Ridge and Lasso
- **Neural Networks** - The deep learning approach for complex patterns

### The Experiments
1. **Synthetic Data**: Created data from a cubic function + controlled noise
2. **Noise Analysis**: Tested how models handle clean vs messy data
3. **ANN Optimization**: Played with early stopping and different activation functions
4. **Real-World Test**: Used the California Housing dataset to predict home prices

## 🚀 Quick Start

Want to run this yourself? Here's how:


# Clone this repository
git clone https://github.com/yacinetalahari/regression-comparison-study.git
cd regression-comparison-study

# Install the required packages
pip install -r requirements.txt

# Open the main notebook
jupyter notebook regression_analysis.ipynb
📁 What's in Here?
text
📦 regression-comparison-study/
├── 📓 regression_analysis.ipynb    # The main notebook - everything happens here!
├── 📊 figs/                        # Cool graphs and visualizations
│   ├── synthetic_datasets.png      # Our synthetic data with/without noise
│   ├── coefficients_comparison.png # How Ridge/Lasso affect coefficients
│   ├── early_stopping_comparison.png # Neural network training optimization
│   └── california_housing_comparison.png # Real-world results
├── 📄 report/
│   └── regression_study_report.pdf # Full project report (fancy LaTeX!)
└── 📋 requirements.txt            # Python packages needed
🔍 Some Interesting Findings
On Synthetic Data
Polynomial regression crushed it (no surprise - it matched the data's true shape!)

Regularized models handled noise much better than their unregularized friends

On Real Data (California Housing)
Neural networks came out on top for complex real-world patterns

Polynomial regression was a strong second place

Simple linear models still held their own pretty well!

Neural Network Insights
Early stopping saved me from training for 100 epochs when 35 was enough

Different activation functions (ReLU, tanh, LeakyReLU) performed surprisingly similarly

ANNs are powerful but definitely need more computational patience

💡 Key Takeaways
Match your model to your data: Polynomial was perfect for synthetic data, ANN excelled with real complexity

Regularization is your friend: Especially when your data has noise or many features

Neural networks deliver: But only if you're willing to wait and tune properly

Keep it simple when you can: Linear models are fast, interpretable, and often good enough

🛠️ Built With
Python - The main programming language

Scikit-learn - For traditional machine learning models

TensorFlow/Keras - For neural network magic

Pandas & NumPy - Data wrangling superheroes

Matplotlib & Seaborn - Making pretty graphs

Jupyter Notebook - Where the experimentation happens

👨‍💻 About Me
I'm Yacine, a computer science student passionate about machine learning and AI. This project was part of my journey to understand the practical side of regression analysis beyond textbook theory.

GitHub: yacinetalahari

📜 License
This project is open source and available under the MIT License.

⭐ If you find this useful, please give it a star! It helps others discover the project and motivates me to keep building and sharing.


