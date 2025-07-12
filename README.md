# 📺 Netflix Movies Exploratory Data Analysis (EDA)

This project is a simple exploratory data analysis (EDA) of Netflix movies dataset using **Python**, **Pandas**, and **Seaborn**.  
It focuses on cleaning, transforming, and visualizing the **Genre** column and answering basic questions about the dataset.

---

## 📌 **Project Objectives**

- Perform basic data cleaning.
- Handle movies with multiple genres.
- Analyze genre distribution.
- Visualize insights using Seaborn.

---

## ❓ **Key Questions Answered**

1️⃣ **What are the unique genres available in Netflix movies?**  
2️⃣ **How can we handle multiple genres in a single column?**  
3️⃣ **Which genres are most common on Netflix?**  
4️⃣ **How to visualize the genre distribution using Seaborn?**

---

## 🛠️ **Key Steps Performed**

✅ **Data Cleaning:**  
- Split the `Genre` column where multiple genres are combined (e.g., *Action, Adventure*).  
- Used `.str.split(', ')` to convert string to list.

✅ **Data Transformation:**  
- Used `explode()` to convert multiple genres into individual rows.
- Reset index to clean up the DataFrame.

✅ **Data Visualization:**  
- Plotted a genre count plot using `Seaborn catplot`.
- Ordered the genres by frequency.
- Added a meaningful title to the plot.

---

## 📊 **Key Python Functions Used**

- `str.split()` — To split genres.
- `explode()` — To expand lists into separate rows.
- `Seaborn catplot()` — To plot categorical data.

---

## 📈 **Sample Visualization**

_(Add a screenshot here if possible!)_

---

## 💡 **Learnings**

- Learned how to **split string columns** into multiple rows.
- Practiced **Pandas explode function**.
- Created **basic plots** using Seaborn.
- Understood the importance of data cleaning before visualization.

---

## 📂 **How to Run**

1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/netflix-movies-eda.git
