# WUNet-BC: Adaptive Image Enhancement for Autonomous Driving

**Unified Wavelet U-Net with Bottleneck Classification (WUNet-BC)**

A deep learning framework for **degradation-aware, adaptive image enhancement** designed for autonomous driving scenarios.

---

## Overview

This project introduces **WUNet-BC**, a unified architecture that integrates:
- Wavelet-based feature decomposition
- U-Net backbone for image restoration
- Bottleneck classification module for degradation awareness

The model identifies the **type and severity of degradation** (e.g., low-light, blur, noise) and applies **adaptive multi-level enhancement**.

---

## Features

- ✅ Degradation-aware enhancement  
- ✅ Adaptive multi-condition restoration  
- ✅ Wavelet + U-Net hybrid architecture  
- ✅ Real-world evaluation (Baghdad dataset)  
- ✅ Generalization tested on standard benchmarks  

---

## Method

**WUNet-BC** combines wavelet decomposition with a U-Net architecture and a bottleneck classifier to guide enhancement dynamically.

> A unified Wavelet U-Net framework with a bottleneck classification module that identifies degradation type and severity, enabling adaptive and multi-level image enhancement.

---

## Dataset

- **Custom Dataset**: Collected from real driving environments in **Baghdad**
-  Includes challenging conditions:
  - Low-light
  - Night
  - Night Glare
  - Rain Streaks
  - Rain Smears

- **Evaluation**:
  - Trained on Baghdad dataset: https://baghdad-ads.yousif.app/
  - Tested on standard benchmark datasets to ensure generalization

---

## Pretrained Model

Download the trained model:

 https://drive.google.com/file/d/15_f0yyRzmR7X_gmVlzcUWKSKOH2kY-SR/view?usp=sharing

## Implementation

The implementation of WUNet-BC is provided as a research-oriented Jupyter Notebook, demonstrating the full pipeline including model architecture, training procedure, and evaluation results.

The notebook is structured to clearly present: Wavelet-based feature extraction
U-Net architecture with bottleneck classification Adaptive image enhancement process  Experimental results on real-world and benchmark datasets

## Paper

Unified Wavelet U-Net with Bottleneck Classification for Adaptive Image Enhancement in Autonomous Driving Systems  
Published at INASS 2026
---

## Contributors

- Dr. Matheel E. Abdulmunim  
- Dr. Nada H. Ali (University of Technology, Baghdad)  
- Prof. Ismail A. Mageed (University of Bradford, UK)  
- Prof. Musheer Ahmad (Jamia Millia Islamia, India)  

---

## Contact

Yousif N. Abbas  
Baghdad, Iraq <br> Email: me@yousif.app
---

## Citation

If you find this work useful, please cite:

```
@article{abbas_uwunet_2026,
  title={Unified Wavelet U-Net with Bottleneck Classification for Adaptive Image Enhancement in Autonomous Driving Systems},
  author={Abbas, Yousif Neamah and Abdulmunim, Matheel Emaduldeen and Ali, Nada Hussain and Ahmad, Musheer and Abdel Mageed, Ismail},
  journal={International Journal of Intelligent Engineering and Systems},
  volume={19},
  number={6},
  pages={105--126},
  year={2026},
  doi={10.22266/ijies2026.0630.07},
  url={https://inass.org/wp-content/uploads/2026/03/2026063007-2.pdf}
}
```

---

## License

This project is open-source.
