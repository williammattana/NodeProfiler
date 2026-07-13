# NodeProfiler

Python script for automated measurement of **paranode** and **node of Ranvier** lengths from **CASPR fluorescence intensity profiles**.

## Overview

This script analyzes line profiles exported from **ImageJ/Fiji**, automatically identifies the two CASPR paranodal peaks, calculates the **full width at half maximum (FWHM)** of each paranode, and estimates the node length from the inner half-maximum crossing points.

## Features

- Automatic detection of the two CASPR peaks
- Savitzky–Golay smoothing for robust peak detection
- FWHM measurement of left and right paranodes
- Node length estimation
- Quality-control visualization of each analyzed profile

## Input

CSV file exported from **ImageJ/Fiji** using **Analyze → Plot Profile**.

## Output

- Left paranode length
- Right paranode length
- Node length
- Peak positions
- Quality-control plot

## Requirements

- Python 3
- NumPy
- Pandas
- SciPy
- Matplotlib

## License

MIT License.
