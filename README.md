<h1>Hi, I'm Zach! 👋</h1>

<h3><a href="https://github.com/zhatz111">Chemical Engineer</a> • <a href="https://www.linkedin.com/in/zacharyhatzenbeller/">Senior Data Scientist</a> • <a href="https://www.youtube.com/@ZachHatz">YouTuber</a> • <a href="https://www.sweetaura.ai">Web Developer</a></h3>

I'm a Senior Data Scientist at GSK working in upstream biopharmaceutical process development, where I build production ML systems for bioreactor modeling, model predictive control, and multivariate analysis. I hold a master's in data science from Johns Hopkins and a bachelor's in chemical engineering from Penn State. Outside of work I'm into algorithmic trading, prediction markets, and shipping side projects.

---

## 🔬 Featured Projects

### [state-space-mpc](https://github.com/zhatz111/state-space-mpc)
Linear and linear time-varying (LTV) state-space Model Predictive Control framework for fed-batch bioreactors. Includes:
- LTI and LTV state-space model identification with cubic spline interpolation between operating partitions
- Open-loop simulation and closed-loop MPC rollouts
- Savitzky-Golay smoothing and PCHIP interpolation for signal upsampling
- Kafka-based automation pipeline for pilot-scale (1000L) deployment

This is the codebase backing my upcoming paper on pilot-scale linear MPC for fed-batch bioreactors.

### [Crowdbite](https://github.com/zhatz111/crowdbite-app)
A social food review platform — think crowd-sourced restaurant reviews built around real diners rather than algorithmic noise. Currently in active development.

### [SweetAura.ai](https://www.sweetaura.ai) — [Repo](https://github.com/zhatz111/AI-Companion-Project)
LLM-powered AI companion website where users chat with characters with distinct personalities. Built with React.js, FastAPI, MongoDB, and deployed on AWS (Amplify + EC2).

### [YouTube Automation](https://github.com/zhatz111/YoutubeAutomation)
Python pipeline that downloads short-form video content (TikTok, Reels, Shorts) and auto-generates captions for republishing.

---

## 🎓 Johns Hopkins MS in Data Science

A selection of coursework and projects from my master's program:

- **[Data Structures](https://github.com/zhatz111/Data-Structures-JHU)** — Prefix/postfix converters (iterative and recursive), Huffman encoding trees, quicksort vs. mergesort benchmarking
- **[Algorithms for Data Science](https://github.com/zhatz111/Data-Science-Masters/tree/main/Algorithms%20for%20Data%20Science)** — Iris dataset analysis, MNIST classification pipeline
- **[Data Engineering Principles and Practice](https://github.com/zhatz111/Data-Science-Masters/tree/main/Data%20Engineering%20Principles%20and%20Practice/final_project)** — End-to-end ETL pipeline: data cleaning, Postgres schema design from an ER diagram, Apache Airflow orchestration, Flask API, and Dockerized deployment
- **[Intro to Python Programming](https://github.com/zhatz111/Masters-in-Bioinformatics-JHU/tree/main/Intro%20to%20Python)**

---

## 💼 What I'm Working On at GSK

I lead a few interconnected data science workstreams in upstream process development:

**Model Predictive Control.** I designed and validated a linear MPC system for fed-batch bioreactors, taking it from in-silico simulation through pilot-scale (1000L) experimental runs. The work spans system identification, LTV modeling to handle batch nonstationarity, and a Kafka-based automation pipeline for real-time deployment.

**Raman Spectroscopy Modeling.** I build PLS and ML models (GPR, SVR, Elastic Net) on Raman spectra for real-time cell metabolite monitoring, with variable selection via genetic algorithms. Recently I've focused on spectra quality control — defining metrics to flag and discard poor-quality spectra before they corrupt downstream models.

**Multivariate Analysis & Platform Fit.** I'm building a three-phase platform fit framework using PCA/PLS in SIMCA to match new drug assets to historical bioreactor batches and back-calculate DoE input ranges, helping inform process development decisions earlier in the pipeline.

---

## 🛠️ Tech I Work With

**Languages:** Python, SQL, MATLAB, LaTeX
**ML / Stats:** scikit-learn, PyTorch, SIMCA, statsmodels, scipy
**Control & Optimization:** CasADi, cvxpy, Kalman/EKF, MPC
**Data & Infra:** Kafka, Postgres, Airflow, Docker, AWS
**Web:** React, FastAPI, MongoDB

---

## 📫 Get in Touch

- **Email:** zhatz111@gmail.com
- **LinkedIn:** [linkedin.com/in/zacharyhatzenbeller](https://www.linkedin.com/in/zacharyhatzenbeller/)
