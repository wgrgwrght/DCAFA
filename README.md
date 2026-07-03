# DCAFA: Differential Community Abundance and Feature Analysis for Histological Images

Please see paper

https://www.biorxiv.org/content/10.64898/2026.04.28.721329v1

@article{wright2026dcafa,
  title={DCAFA: Differential Community Abundance and Feature Analysis for Histological Images},
  author={Wright, George and Keller, Piotr and Muter, Joanne and Brosens, Jan and Tejpar, Sabine and Minhas, Fayyaz},
  journal={bioRxiv},
  pages={2026--04},
  year={2026},
  publisher={Cold Spring Harbor Laboratory}
}

# DCAFA: Differential Community Abundance and Feature Analysis

**DCAFA** is a statistical framework for analysing histological and spatial biomedical data by jointly modelling **community composition** and **feature-level associations**.

It is designed to identify meaningful biological patterns that arise from **groups of structures (e.g. cells, glands, tissue regions)** rather than individual features alone.

---

## 📄 Overview

Histological images contain complex spatial organisation, where clinically relevant signals often emerge from **changes in the composition of structures** rather than isolated measurements.

DCAFA addresses this by:

* Grouping instances into **latent communities** (shared morphological or phenotypic patterns)
* Quantifying how these communities vary across outcomes
* Linking **instance-level features** to outcomes both globally and within communities

The method combines:

* **Differential community abundance analysis**
* **Feature attribution analysis**

within a unified statistical framework based on regression models.

> This enables interpretable inference using effect sizes, confidence intervals, and false discovery rate control.

---

## 🔬 Key Features

* 🧩 **Community Detection**
  Identifies recurring structural patterns in histological data

* 📊 **Differential Abundance Testing**
  Detects communities enriched or depleted across conditions

* 🔎 **Feature Attribution**
  Quantifies how features relate to outcomes globally or within specific communities

* ⚙️ **Statistical Modelling**
  Uses generalised linear and mixed-effects models with covariate adjustment

* 📈 **Interpretable Outputs**
  Provides effect sizes, confidence intervals, and FDR-controlled results

---

## 🧠 Applications

DCAFA has been applied to multiple biomedical domains, including but not limited to:

* Histopathology (e.g. endometrial tissue)
* Spatial transcriptomics
* Multiplex immunofluorescence imaging
* Cell-type composition analysis in cancer

These analyses reveal **compositional shifts and context-specific feature associations** not captured by conventional feature-based methods.

---

## 🚀 Installation

```bash
git clone https://github.com/wgrgwrght/DCAFA.git
cd DCAFA
```

*(Add environment setup instructions here if applicable — e.g. conda, pip, Docker)*

---

## ⚡ Quick Start

```python
# Example usage (placeholder)

from dcafa import DcafaModel

model = DcafaModel()
model.fit(data, metadata)

results = model.analyse()
model.plot(results)
```

*(Replace with real usage examples from the repo)*

---

## 📊 Workflow

1. Input histological or spatial data with associated metadata
2. Learn latent communities from instance-level features (this is left to the user)
3. Perform:

   * Community abundance analysis
   * Feature attribution analysis
4. Interpret statistically significant results

---

## 📖 Citation

If you use DCAFA, please cite:

```
Wright, G., Keller, P., Muter, J., Brosens, J., Tejpar, S., & Minhas, F. (2026).
DCAFA: Differential Community Abundance and Feature Analysis for Histological Images.
bioRxiv.
```

---

## 📜 License

*(Specify license here — e.g. MIT, GPL, etc.)*

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## 📬 Contact

For questions or collaborations, please contact the authors or open a GitHub issue.

