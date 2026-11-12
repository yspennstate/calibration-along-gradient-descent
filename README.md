# Calibration along gradient descent in Gaussian tanh random-feature classifiers

Yitzchak Shmalo, Einstein Institute of Mathematics, The Hebrew University of Jerusalem

- Paper: [T357_Calibration_Along_Gradient_Descent.pdf](T357_Calibration_Along_Gradient_Descent.pdf)
- LaTeX source: [T357_Calibration_Along_Gradient_Descent.tex](T357_Calibration_Along_Gradient_Descent.tex)

Full-batch gradient descent on cross-entropy in a two-layer Gaussian random-feature model with tanh activation and a logistic single-index teacher. At every fixed iteration and all proportional sample, input and width ratios, an explicit recursion gives the asymptotic population risk and the exact calibration of the trained model. In a sample-rich regime the approximation is uniform over all times; in a strongly overparameterized regime there is a calibration floor at every stopping time, and the risk-optimal first step is strictly overconfident on average.

Build with `xelatex T357_Calibration_Along_Gradient_Descent.tex` (twice).

The paper is part of the Math Brain project: [repository](https://github.com/yspennstate/math-brain-public), [paper](https://github.com/yspennstate/math-brain-public/tree/main/papers/math-brain-2026-10-24). It is released under CC BY 4.0.
