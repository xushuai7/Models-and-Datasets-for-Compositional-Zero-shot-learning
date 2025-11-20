# Models and Datasets for Compositional Zero-Shot Learning

This repository summarizes the benchmark datasets and CZSL models used in our paper.

---

## 1. Datasets

We evaluate models on three standard CZSL benchmarks.
|Y_s| and |Y_u| denote the numbers of seen and unseen attribute–object compositions, respectively, and |X| denotes the number of images in each split.
All datasets follow the standard splits proposed by Purushwalkam et al.


### 1.1 Dataset Statistics

| Dataset   | Train (\|Y<sub>s</sub>\|, \|X\|) | Validation (\|Y<sub>s</sub>\|, \|Y<sub>u</sub>\|, \|X\|) | Test (\|Y<sub>s</sub>\|, \|Y<sub>u</sub>\|, \|X\|) |
|----------|----------------------------------|---------------------------------------------------------|----------------------------------------------------|
| MIT-States | (1,262, 30,338)                | (300, 300, 10,420)                                      | (400, 400, 12,995)                                 |
| UT-Zappos  | (83, 22,998)                   | (15, 15, 3,214)                                         | (18, 18, 2,914)                                    |
| C-GQA      | (5,592, 26,920)                | (1,252, 1,040, 7,280)                                  | (888, 923, 5,098)                                  |

### 1.2 Dataset Links

- **MIT-States**: https://web.mit.edu/phillipi/Public/states_and_transformations/index.html  
- **UT-Zappos50k**: https://vision.cs.utexas.edu/projects/finegrained/utzap50k/  
- **C-GQA**: https://github.com/ExplainableML/czsl  

---

## 2. CZSL Models

The following models are included in our closed-world CZSL comparison (see the paper’s table for detailed S/U/H/AUC metrics on each dataset).

### 2.1 Model List

| Models   | Source (Venue & Year) | Paper | Code |
|----------|------------------------|-------|------|
| Aop      | ECCV 2018             | [Paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Tushar_Nagarajan_Attributes_as_Operators_ECCV_2018_paper.html) | [Code](https://github.com/Tushar-N/attributes-as-operators) |
| CompCos  | CVPR 2021             | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Mancini_Open_World_Compositional_Zero-Shot_Learning_CVPR_2021_paper.html) | [Code](https://github.com/kim-min-jun/Compositional-Zero-shot-Learning) |
| OADis    | CVPR 2022             | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Saini_Disentangling_Visual_Embeddings_for_Attributes_and_Objects_CVPR_2022_paper.html) | [Code](https://github.com/nirat-saini/Disentangling-Visual-Embeddings-for-AO) |
| CAPE     | WACV 2023             | [Paper](https://openaccess.thecvf.com/content/WACV2023/html/Khan_Learning_Attention_Propagation_for_Compositional_Zero-Shot_Learning_WACV_2023_paper.html) | [Code](https://github.com/ans92/CAPE) |
| CGE      | CVPR 2021             | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Naeem_Learning_Graph_Embeddings_for_Compositional_Zero-Shot_Learning_CVPR_2021_paper.html) | [Code](https://github.com/kim-min-jun/Compositional-Zero-shot-Learning) |
| TMN      | ICCV 2019             | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Purushwalkam_Task-Driven_Modular_Networks_for_Zero-Shot_Compositional_Learning_ICCV_2019_paper.html) | [Code](https://github.com/facebookresearch/taskmodularnets) |
| GIPCOL   | WACV 2024             | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Xu_GIPCOL_Graph-Injected_Soft_Prompting_for_Compositional_Zero-Shot_Learning_WACV_2024_paper.html) | [Code](https://github.com/xugy16/GIPCOL-czsl) |
| CSP      | ICLR 2023             | [Paper](https://arxiv.org/abs/2204.03574) | [Code](https://github.com/BatsResearch/csp) |
| SymNet   | CVPR 2020             | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Symmetry_and_Group_in_Attribute-Object_Compositions_CVPR_2020_paper.html) | [Code](https://github.com/DirtyHarryLYL/SymNet) |
| SCEN     | CVPR 2022             | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Siamese_Contrastive_Embedding_Network_for_Compositional_Zero-Shot_Learning_CVPR_2022_paper.html) | [Code](https://github.com/XDUxyLi/SCEN-master) |
| ADE      | CVPR 2023             | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Hao_Learning_Attention_As_Disentangler_for_Compositional_Zero-Shot_Learning_CVPR_2023_paper.html) | [Code](https://github.com/haoosz/ade-czsl) |
| CANet    | CVPR 2023             | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Learning_Conditional_Attributes_for_Compositional_Zero-Shot_Learning_CVPR_2023_paper.html) | [Code](https://github.com/zhangyongshun/CA-Net) |
| DFSP     | CVPR 2023             | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Lu_Decomposed_Soft_Prompt_Guided_Fusion_Enhancing_for_Compositional_Zero-Shot_Learning_CVPR_2023_paper.html) | [Code](https://github.com/Forest-art/DFSP) |
| HPL      | IJCAI 2023            | [Paper](https://www.ijcai.org/proceedings/2023/) | Code (refer to paper) |
| Troika   | CVPR 2024             | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_Troika_Multi-Path_Cross-Modal_Traction_for_Compositional_Zero-Shot_Learning_CVPR_2024_paper.html) | [Code](https://github.com/siteng-huang/Troika) |
| CDS-CZSL | CVPR 2024             | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Context-Based_and_Diversity-Driven_Specificity_in_Compositional_Zero-Shot_Learning_CVPR_2024_paper.html) | Code (official link TBD) |
| PLID     | ECCV 2024             | [Paper](official ECCV 2024 paper link) | [Code](official PLID GitHub link) |
| RA       | AAAI 2024             | [Paper](official AAAI 2024 paper link) | [Code](official RA GitHub link) |
| ProLT    | AAAI 2024             | [Paper](official AAAI 2024 paper link) | [Code](official ProLT GitHub link) |
| MSCI     | arXiv 2025            | [Paper](https://arxiv.org/abs/2505.10289) | [Code](https://github.com/ltpwy/MSCI) |
| TSCA     | arXiv 2024            | [Paper](https://arxiv.org/abs/2408.08703) | [Code](official TSCA GitHub link) |



