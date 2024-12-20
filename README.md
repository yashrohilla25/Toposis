# Toposis

## Objective
This project applies the TOPSIS technique to evaluate and rank pretrained models for text summarization based on multiple criteria.

## Evaluation Criteria
1. **Accuracy:** Higher is better.
2. **BLEU Score:** Higher is better.
3. **Inference Time:** Lower is better.
4. **Model Size:** Lower is better.

## Methodology
TOPSIS ranks models by comparing their performance against an ideal solution and a negative-ideal solution.


## Visualization
![Bar Chart of Closeness Scores](closeness_scores.png)

## Files
1. `topsis_analysis.py` - Python script for TOPSIS implementation.
2. `topsis_results.csv` - Results of the analysis.
3. `closeness_scores.png` - Visualization of closeness scores.
