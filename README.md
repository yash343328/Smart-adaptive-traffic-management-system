# 🚦 Smart Adaptive Traffic Management System (SATMS)

> AI-powered intelligent traffic control system using a Reinforcement Learning-inspired algorithm (ARIA) to dynamically optimize traffic signals in real-time.
* * *

## 📌 Overview

The **Smart Adaptive Traffic Management System (SATMS)** is an advanced simulation-based traffic control system designed to solve urban congestion problems.

Traditional traffic lights operate on fixed timers, leading to inefficiencies and increased wait times. SATMS introduces a **dynamic, AI-driven approach** that adapts signal timings based on real-time traffic conditions.

* * *

## 🚀 Key Features

- 🧠 **ARIA Algorithm (Adaptive Reinforcement Intersection Algorithm)**
  - Inspired by Q-Learning
  - Real-time decision making without offline training

- 🚗 **Real-time Traffic Simulation**
  - Simulates vehicles, congestion, and lane density
  - IoT-like sensor data generation

- 🚨 **Emergency Vehicle Preemption**
  - Detects emergency vehicles
  - Creates a "Green Wave" across intersections

- 🌐 **Multi-Intersection Coordination**
  - Supports connected intersections
  - Optimized traffic flow across city grids

- 📊 **Performance Analytics**
  - Wait time, congestion, throughput
  - Efficiency scoring and reporting

- 📈 **Automatic Report Generation**
  - Detailed system performance summary
  - Traffic heatmaps and signal states

* * *

## 🧪 Research Contributions

1. Adaptive Reinforcement Learning-based traffic control (ARIA)
2. Multi-agent coordination between intersections
3. Predictive congestion scoring using sensor analytics
4. Emergency vehicle handling with priority routing
5. Queue-based wait time estimation using M/D/1 model

* * *

## 🛠️ Technologies Used

- **Language:** Java 17+
- **Libraries:**  
  - `java.util.concurrent` – Multithreading  
  - `java.time` – Time handling  
  - `java.util.logging` – Logging  
  - `java.io` – Report generation  
  - `java.net` – Simulated IoT communication  

> ⚠️ No external libraries used – pure Java implementation.


* * *

## ⏱️ Simulation Details



-   Default runtime: **30 seconds**
-   Network: **6 intersections (2x3 grid)**
-   Real-time adaptive decision making every 2 seconds

* * *

## 📊 Sample Output



-   Real-time logs
-   Traffic signal changes
-   Congestion analytics
-   Final performance report saved as:

    SATMS_Report_YYYYMMDD.txt

* * *

## 📈 Performance Improvements (Simulation)



| Metric | Improvement |
| --- | --- |
| Average Wait Time | ⬇️ 28–42% |
| Traffic Throughput | ⬆️ 15–25% |
| Emergency Response | < 5 sec |

* * *

## 🧠 Algorithm (ARIA)



-   State Space: 625 combinations
-   Actions: 5 signal strategies
-   Learning: Online Temporal Difference Learning
-   Exploration: Epsilon-Greedy

* * *

## 🎯 Use Cases



-   Smart Cities
-   Traffic Simulation Research
-   AI-based Infrastructure Optimization
-   Urban Planning Systems

* * *

## 🔮 Future Improvements


-   Integration with real IoT traffic sensors
-   GUI dashboard (JavaFX / Web)
-   Machine Learning model training with real datasets
-   Cloud-based deployment

* * *

## 👨‍💻 Author


**Yash Jain**  

* * *

## 📜 License


This project is for academic and research purposes.

* * *

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
