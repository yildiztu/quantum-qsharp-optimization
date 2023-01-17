# Quantum Q# Optimization
An example optimization problem with a quadratic objective function and both linear and quadratic constraints

This code defines an optimization problem with a quadratic objective function f(x) represented by a quadratic form 0.5 * x^T A x + b^T x, linear constraints g(x) represented by Cx - d and quadratic constraints h(x) represented by x[i]^2. It then uses the Q# Optimizer to solve the optimization problem and store the result in the input variable x. Note that this code is an example and you need to provide appropriate input such as matrix A, b, C, d and qubits qs according to your problem. 
