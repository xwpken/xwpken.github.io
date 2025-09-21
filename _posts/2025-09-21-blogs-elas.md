---
layout: post
title: "A Brief Introduction to Linear Elasticity"
date: 2025-09-21
categories: blogs
author: "Copilot"
---

Linear elasticity is a fundamental theory in solid mechanics that describes how materials deform under applied forces, assuming the deformations are small and the material returns to its original shape when the load is removed.

<!--more-->

## Basic Concepts

The relationship between stress $\sigma$ and strain $\varepsilon$ in a linear elastic material is given by Hooke's law:

$$
\sigma = E \varepsilon
$$

where $E$ is the Young's modulus, a material property that measures stiffness.

For three-dimensional problems, the generalized Hooke's law can be written as:

$$
\sigma_{ij} = C_{ijkl} \varepsilon_{kl}
$$

where $C_{ijkl}$ is the fourth-order elasticity tensor.

## Strain and Displacement

The strain tensor is defined in terms of the displacement field $u$ as:

$$
\varepsilon_{ij} = \\frac{1}{2} \\left( \\frac{\\partial u_i}{\\partial x_j} + \\frac{\\partial u_j}{\\partial x_i} \\right)
$$

## Governing Equations

The equilibrium equations (neglecting body forces) are:

$$
\\nabla \\cdot \\sigma = 0
$$

Boundary conditions and material properties complete the mathematical description of a linear elastic problem.

---

Linear elasticity forms the basis for more advanced theories in continuum mechanics and is widely used in engineering analysis and design.