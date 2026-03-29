# **Maksim Nizhnikov**
## **Contacts**
* Phone: +375 (44) 774-27-63
* Email: diocool71@gmail.com
* LinkedIn: [linkedin.com/in/xdoxi1](https://linkedin.com/in/xdoxi1)
* GitHub: [github.com/xdoxi1](github.com/xdoxi1)
* Location: Mahilyow, Mogilev, BY
## **Professional Summary**
Motivated mathematics student from Mahilyow, Belarus, specializing in applied mathematics, probability theory, combinatorics, and numerical methods for biological modeling. Goal: apply Python simulations to population dynamics and differential equations. Strong analytical skills from projects in Euler's method and Gaussian elimination.
## **Skills**
* Programming: Python (numpy, scipy, matplotlib)
* Frameworks/Tools: Jupyter Notebooks, Git
* Math Methods: ODE solvers (Euler), linear algebra (Gaussian elimination), probability
* Modeling: Population dynamics, stability analysis 
## **Code Example**
Euler's method for population growth ODE dy/dt = k*y
```import numpy as np
import matplotlib.pyplot as plt

def euler_method(y0, k, t, dt):
    n = int(t / dt)
    y = np.zeros(n + 1)
    y[0] = y0
    for i in range(n):
        y[i+1] = y[i] + k * y[i] * dt
    return y

y0, k, t, dt = 1.0, 0.1, 10, 0.01
y = euler_method(y0, k, t, dt)
plt.plot(np.linspace(0, t, len(y)), y)
plt.show()
```
## **Experience & Projects**
1. **CV Website** — Semantic HTML CV.\
[View](cv.html) | [GitHub](https://github.com/xdoxi1/WebProgramming)
2. **Population Dynamics** — Lotka-Volterra simulation. \
[GitHub](https://github.com/xdoxi1)
3. **Gaussian Elimination**  Linear solver. \
[GitHub](https://github.com/xdoxi1)
## **Courses & Training** 
* Probability Theory (University of Mahilyow)
* Numerical Methods for ODEs (Coursera)
* Scientific Computing with Python (freeCodeCamp)