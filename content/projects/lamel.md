---
title: "LAMeL: meta-learning for molecular property prediction"
weight: 1
summary: "An interpretable meta-learning method that improves linear models for molecular property prediction when labeled data are scarce. Up to 25x accuracy gains; adopted across three LANL divisions."
description: "LAMeL: interpretable meta-learning for molecular property prediction in data-scarce regimes, by Yulia Pimonova (Los Alamos National Laboratory)."
---

**Problem.** Many molecular properties of practical interest have only a handful of measured examples, too few to train an accurate model from scratch.

**Method.** LAMeL meta-learns linear models across related property-prediction tasks, assuming they share a common subspace, so each new task borrows structure from the others while the model stays interpretable. It started as my 2023 summer internship project at LANL, validated on experimental and computational datasets from 3K to 134K data points.

**Result.** Up to 25x accuracy gain in data-scarce regimes, published in *Digital Discovery* (2026). I extended the approach to PFAS property prediction, and it has been adopted across three LANL divisions.

**Links:** [Paper (DOI)](https://doi.org/10.1039/D5DD00443H) · [arXiv](https://arxiv.org/abs/2509.13527) · [Code (in minervachem)](https://github.com/lanl/minervachem/tree/main/lamel)
