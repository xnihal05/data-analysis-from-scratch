# Python Data Analysis — Learning Journey

Hey! This repo is my personal learning log where I'm picking up Python for data analysis from scratch.  
Right now it covers **Pandas** and **NumPy** — and I'll keep adding more as I go.

---

## - What's Inside

| File | Topic |
|------|-------|
| `Day1.ipynb` | Pandas Basics |
| `Day2.ipynb` | Real Dataset + Data Cleaning |
| `Day3__Handson_.ipynb` | Pandas Practice (Hands-on) |
| `Day_4.ipynb` | NumPy Fundamentals |
| `Day_5.ipynb` | NumPy Practice (Hands-on) |

---

## - Day-by-Day Breakdown

### Day 1 — Pandas Basics
Got started with Pandas and learned how data is structured in it.

- Created DataFrames manually using dictionaries and lists
- Understood what a **Series** is (basically a single column)
- Added new columns to an existing DataFrame
- Used `.max()`, `.min()`, `.describe()` to get quick stats
- Learned the difference between **`loc`** (label-based) and **`iloc`** (index-based) for selecting data
- Practiced slicing rows and columns

---

### Day 2 — Real Dataset + Data Cleaning
Worked on a real-world powerlifting dataset and learned how to clean messy data.

- Loaded a CSV file using `pd.read_csv()`
- Explored data with `.head()`, `.tail()`, `.sample()`, `.info()`, `.describe()`
- Renamed columns using `.rename()`
- Handled **null values** — dropped them or filled them with mean/median/0
- Removed **duplicate rows** with `.drop_duplicates()`
- Filtered data based on conditions (single and multiple at once using `&` and `|`)

---

### Day 3 — Pandas Hands-on Practice
Put Day 1 and Day 2 knowledge to the test with practice problems.

- Converted Python lists, tuples, and sets into Pandas Series (and figured out why sets cause issues — they're unordered!)
- Practiced `.head()`, `.tail()`, and updating values at specific index positions
- Built DataFrames from dictionaries and renamed columns
- Filtered rows by conditions (e.g. age ≥ 19)
- Loaded another real dataset (`adult_data`), explored it fully, and cleaned all null + duplicate values
- Used `.shape` to check total rows and columns

---

### Day 4 — NumPy Fundamentals
Switched to NumPy and understood why it exists in the first place.

- Learned why NumPy arrays are faster and lighter than Python lists  
  *(Python lists are slow; NumPy is built on C/C++ so it uses a compiler, not an interpreter)*
- Created **0D, 1D, 2D, and 3D arrays** and checked their `.shape` and `.ndim`
- Understood NumPy's type hierarchy: `int < float < string`
- Learned **indexing** and **slicing** across 1D, 2D, and 3D arrays
- Used **`.reshape()`** to change the shape of an array
- Explored special arrays: `np.zeros()`, `np.ones()`, `np.full()`, `np.identity()`, `np.eye()`
- Generated random numbers with `np.random.randint()` and `np.random.choice()`
- Did arithmetic on arrays (`+`, `-`, `*`, `/`) — unlike lists, arrays actually calculate!
- Used `.sum()`, `.mean()`, `.median()`, `np.sort()`, and `.flatten()`

---

### Day 5 — NumPy Hands-on Practice
Solidified NumPy basics with focused exercises.

- Created int and float arrays with specific dtypes
- Built 0D, 1D, 2D, and 3D arrays and checked their shape
- Made a 2×5 zeros array and a 2×5 array filled with 5 using `np.full()`
- Generated 25 random integers between 0–100
- Created a 2×3 random matrix and reshaped it to 3×2
- Made a 3×3 matrix of all ones

---

## - Coming Up

### Day 6 — Data Visualization (in progress)
Starting with **Matplotlib** and/or **Seaborn** to bring the data to life visually.  
Charts, plots, graphs — all coming soon.

---

## 🛠 How to Run

1. Make sure you have Python installed
2. Install the required libraries:
   ```
   pip install pandas numpy jupyter
   ```
3. Open any notebook:
   ```
   jupyter notebook Day1.ipynb
   ```

---

## - Tools Used

- **Python 3.12**
- **Pandas** — for working with tables and datasets
- **NumPy** — for numerical operations and arrays
- **Jupyter Notebook** — for writing and running code interactively
