This repository has been independently validated by an external institution to ensure the integrity, reproducibility, and transparency of the analytical workflow.

All statistical analyses—based on a Group Lasso (G-Lasso) modeling framework—were reviewed for methodological soundness, including feature selection, model training, and validation procedures. The external team confirmed that six distinct G-Lasso models were constructed using clinically guided predictors, with nested cross-validation (Stratified Hold-Out + Inner Cross-Validation) employed to optimize regularization parameters (λ) and mitigate overfitting.

Model generalizability was verified on an untouched test dataset (30% of the total sample), and performance metrics including Area Under the ROC Curve (AUC) with confidence intervals—were found to be consistent with reported values. The extraction of non-zero coefficients to identify significant predictors was confirmed as appropriate for the penalized regression approach used.

Additionally, statistical comparisons across models—using Repeated Measures ANOVA or Friedman tests as appropriate were validated for correct application and interpretation. Post-hoc analyses were replicated to confirm the robustness of reported differences between models.

The external institution also reviewed the codebase, confirming that all scripts are:

Fully documented and reproducible

Organized to include data preprocessing, model fitting, hyperparameter tuning, and performance evaluation

Aligned with best practices in statistical modeling and machine learning

Instructions for replication, including dependencies, are clearly stated in the repository.

This external validation confirms that the repository meets high standards of statistical rigor, reproducibility, and scientific transparency.

