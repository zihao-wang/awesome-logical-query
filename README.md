# awesome-logical-query-answering
A collection of resources on the topic of Complex Logical Query Answering

TODO: Insert an image from the paper


## :scroll: Categorization of papers

### Modalities


<details>
  <summary>Triple-based KGs (28)</summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
  3. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  4. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  5. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  6. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  7. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  8. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  9. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  10. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  11. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  12. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  13. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  14. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  15. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  16. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  17. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  18. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  19. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  20. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  21. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  22. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  23. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  24. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  25. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  26. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  27. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  28. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

  </details> 

<details>
  <summary>Hyper-relational KGs (1)</summary>

  1. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022

</details>

<details>
  <summary>Hyper-graphs and Multi-modal graphs (0)</summary>

  0. None as of Sept 2022
  
</details>


### Reasoning Domain


<details>
  <summary>Discrete (Entities only) (28) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
  3. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  4. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  5. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  6. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  7. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  8. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  9. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  10. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  11. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  12. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  13. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  14. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  15. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  16. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  17. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  18. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  19. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  20. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  21. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  22. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  23. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  24. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  25. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  26. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  27. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  28. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
</details>

<details>
  <summary>Predict Qualifier Entities for Hyper-Relational KGs (0)</summary>

  0. None as of Sept 2022
  
</details>
  
<details>
  <summary>Discrete Temporal (Entities + Dates) (1)</summary>

  1. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  
</details>

<details>
  <summary>Discrete + Continuous (Entities + string/numerical Literals) (0)</summary>

  0. None as of Sept 2022
  
</details>



### Logical Expressiveness


<details>
  <summary>EPFO (15) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
  3. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  4. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  5. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  6. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  7. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  8. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  9. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  10. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  11. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  12. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  13. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  14. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  15. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022

</details>

<details>
  <summary>EPFO + Negation queries (11) </summary>

  1. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  2. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  3. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  4. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  5. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  6. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  7. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  8. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  9. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  10. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  11. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
</details>

<details>
  <summary>Class / relation axioms (3) </summary>

  1. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  2. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  3. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
</details>


### Learning

<details>
  <summary>Transductive (27) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
  3. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  4. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  5. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  6. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  7. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  8. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  9. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  10. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  11. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  12. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  13. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  14. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  15. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  16. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  17. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  18. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  19. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  20. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  21. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  22. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  23. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  24. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  25. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  26. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  27. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
</details>

<details>
  <summary>Inductive (limited) (1) </summary>

  1. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022

</details>

<details>
  <summary>Inductive (2) </summary>

  #### Target Inductive (0)
  0. None as of Sept 2022

  #### Any node on the reasoning path inductive (2)
  1. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  2. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  

</details>


### Modeling

<details>
  <summary>End-to-end Neural (6) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  4. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  5. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  6. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022

</details>

<details>
  <summary>Neuro-Symbolic (19) </summary>

  #### GNN-based (3)
  1. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  2. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  3. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022

  #### Geometric (6)
  1. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020
  2. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  3. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  4. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  5. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  6. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022

  #### Distributions (3)
  1. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  2. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  3. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
   

  #### Entity-centric or T-norms (7)

  1. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  2. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  3. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  4. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  5. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  6. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  7. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>

<details>
  <summary>Symbolic (2) </summary>

  1. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  2. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022

</details>


### Query Patterns

<details>
  <summary>Fixed patterns from specific datasets (24) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
  3. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  4. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  5. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  6. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  7. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  8.  [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  9.  [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  10. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  11. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  12. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  13. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  14. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  15. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  16. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  17. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  18. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  19. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  20. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  21. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  22. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  23. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  24. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>

<details>
  <summary>Arbitrary query DAGs (4) </summary>

  1. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  2. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  3. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  4. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022

</details>

<details>
  <summary>Extended query DAGs (eg, hyper-relational) (1) </summary>

  1. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022

</details>

<details>
  <summary>Allowing cyclic query patterns (0) </summary>

  0. None as of Sept 2022

</details>

<details>
  <summary>Arbitrary query shapes (0) </summary>

  0. None as of Sept 2022

</details>


### Query Operators

Progressive scale of supported operators. That is, all models listed under the "NOT" category also support JOIN and UNION.

<details>
  <summary>PROJECTION + JOIN (intersection) (7) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019 
  3. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  4. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  5. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  6. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  7. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022

</details>

<details>
  <summary> + UNION (9) </summary>

  1. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020
  2. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  3. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  4. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  5. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  6. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz) ICLR’21
  7. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  8. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  9. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022

</details>

<details>
  <summary> + NOT (negation) (13) </summary>

  1. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  2. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  3. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  4. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  5. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  6. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  7. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  8. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  9. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  10. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  11. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  12. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  13. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>

<details>
  <summary> + FILTER over discrete outputs (filtering entities) (0) </summary>

  0. None as of Sept 2022

</details>

<details>
  <summary> + FILTER over discrete + continuous outputs (+ filtering literals) (0) </summary>

  0. None as of Sept 2022

</details>

<details>
  <summary> + AGGREGATIONS (GROUP BY, ORDER BY, etc) (0) </summary>

  0. None as of Sept 2022

</details>


### Return Type (Projections)

<details>
  <summary> Final node only (6) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  4. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  5. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  6. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022

</details>

<details>
  <summary> Arbitrary non-anchor nodes (intermediate variables) (21) </summary>
 
  1. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  2. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  3. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  4. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  5.  [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  6.  [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  7.  [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  8.  [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  9.  [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  10. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  11. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  12. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  13. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  14. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  15. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  16. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  17. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  18. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  19. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  20. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  21. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>


### Training

<details>
  <summary> End-to-end trainable (28) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
  3. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  4. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  5. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  6. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  7. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  8. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  9. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  10. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  11. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  12. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  13. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  14. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  15. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  16. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  17. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  18. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  19. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  20. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  21. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  22. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  23. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  24. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  25. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  26. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  27. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  28. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>

<details>
  <summary> Inference-only (decoders) (1) </summary>

  1. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz) ICLR’21

</details>

### Metrics

- Original metrics: ROC AUC and Average Percentile Rank over 1000 negative samples. 
  - Proposed by original [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf) (NeurIPS 2018), used by [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA). **Not used after**.
- Generalization: predicting hard answers (MRR / Hits@k).
  - Introduced by [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS) (ICLR 2020). **Standard metric**.
- Generalization: from ranking to binary classification
  - Proposed in [Approximate knowledge graph query answering: from ranking to binary classification](https://library.oapen.org/bitstream/handle/20.500.12657/48251/9783030723088.pdf?sequence=1#page=114)
- Entailment: faithfulness - ability to recover easy answers (no link prediction) (MRR / Hits@k)
  - Proposed by [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html) (NeurIPS 2020)
- Estimating the cardinality of answer set size (Spearman's rank correlation, MAPE)
- Predicting easy answers before hard answers (ROC-AUC)


## 📈 Datasets and Benchmarking

### BetaE Datasets

The main difference with Query2Box datasets: queries in the BetaE datasets have less than 100 answers. Has queries with negation.

Introduced in [Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB15k    | 14,951 | 1,345 | 483,142 | 50,000 | 59,071 | 592,213 |
  | FB15k237 | 14,505 | 237   | 272,115 | 17,526 | 20,438 | 310,079 |
  | NELL995  | 63,361 | 200   | 114,213 | 14,324 | 14,267 | 142,804 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p/2p/3p/2i/3i  | 2in/3in/inp/pin/pni  | 1p | others | 1p | others |
  | FB15k    | 273,710 | 27,371 | 59,097 | 8,000 | 67,016 | 8,000 |
  | FB15k237 | 149,689 | 14,968 | 20,101 | 5,000 | 22,812 | 5,000 |
  | NELL995  | 107,982 | 10,798 | 16,927 | 4,000 | 17,034 | 4,000 | 

</details>

<details>
  <summary> Average Number of Answers </summary>

  | Dataset | 1p | 2p |  3p | 2i |  3i | ip | pi | 2u | up | 2in | 3in | inp | pin | pni |
  |---------|---:|---:|----:|---:|----:|---:|---:|---:|---:|---:|----:|---:|---:|---:|
  | FB15k   | 1.7 | 19.6 | 24.4 | 8.0 | 5.2 | 18.3 | 12.5 | 18.9 | 23.8 | 15.9 | 14.6 | 19.8 | 21.6 | 16.9 |
  | FB15k237 | 1.7 | 17.3 | 24.3 | 6.9 | 4.5 | 17.7 | 10.4 | 19.6 | 24.3 | 16.3 | 13.4 | 19.5 | 21.7 | 18.2 |
  | NELL995 | 1.6 | 14.9 | 17.5 | 5.7 | 6.0 | 17.4 | 11.9 | 14.9 | 19.0 | 12.9 | 11.1 | 12.9 | 16.0 | 13.0 | 
  
</details>

### Query2Box Datasets

Introduced in [Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020. 

EPFO queries are considered **easier** than BetaE datasets. Doesn't have queries with negations.

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB15k    | 14,951 | 1,345 | 483,142 | 50,000 | 59,071 | 592,213 |
  | FB15k237 | 14,505 | 237   | 272,115 | 17,526 | 20,438 | 310,079 |
  | NELL995  | 63,361 | 200   | 114,213 | 14,324 | 14,267 | 142,804 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p  | others  | 1p | others | 1p | others |
  | FB15k    | 273,710 | 273,710 | 59,097 | 8,000 | 67,016 | 8,000 |
  | FB15k237 | 149,689 | 149,689 | 20,101 | 5,000 | 22,812 | 5,000 |
  | NELL995  | 107,982 | 107,982 | 16,927 | 4,000 | 17,034 | 4,000 | 

</details>

<details>
  <summary> Average Number of Answers </summary>

  | Dataset | 1p | 2p |  3p | 2i |  3i | ip | pi | 2u | up | 
  |---------|---:|---:|----:|---:|----:|---:|---:|---:|---:|
  | FB15k   | 10.8 | 255.6 | 250.0 | 90.3 | 64.1 | 593.8 | 190.1 | 27.8 | 227.0 | 
  | FB15k237 | 13.3 | 131.4 | 215.3 | 69.0 | 48.9 | 593.8 | 257.7 | 35.6 | 127.7 | 
  | NELL995 | 8.5 | 56.6 | 65.3 | 30.3 | 15.9 | 310.0 | 144.9 | 14.4 | 62.5 | 
  
</details>

### Type-Aware Datasets

- TODO
- TODO
- YAGO 4 (Abductive), introduced in [TAR](https://github.com/lilv98/TAR)
- DBpedia (Abductive), introduced in [TAR](https://github.com/lilv98/TAR)

### Very Large Datasets

Introduced in [SMORE: Knowledge Graph Completion and Multi-hop Reasoning in Massive Knowledge Graphs](https://arxiv.org/abs/2110.14890), KDD 2022.

Training queries are sampled on-the-fly during training due to the huge size of underlying graphs. 
TODO: confirm with Hongyu the number of validation / test queries.

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB400k    | 409,829 | 918 | 1,075,837 | 537,917 | 537,917 | 2,151,671 |
  | WikiKG2 | 2,500,604 | 535   | 16,109,182 | 429,456 | 598,543 | 17,137,181 |
  | Freebase  | 86,054,361 | 14,824  | 304,727,650 | 16,929,318 | 16,929,308 | 338,586,276 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries |  Validation | Validation |  Test | Test |
  |---------|------------:|-----------:|------:|-----:|
  | Dataset |  1p | others | 1p | others |
  | FB400k    | TODO | TODO | TODO | TODO |
  | WikiKG2 | TODO | TODO | TODO | TODO |
  | Freebase  | TODO | TODO | TODO | TODO |

</details>

### Inductive Datasets



### Dataset tools

- [Graph Query Sampler](https://github.com/miselico/graph_query_sampler): Not a method, rather a dataset generator


## :wrench: Implementations

- [KGReasoning](https://github.com/snap-stanford/KGReasoning): GQE, Query2Box, BetaE
- [CQD](https://github.com/pminervini/KGReasoning): GQE, Query2Box, BetaE, CQD
- [StarQE](https://github.com/DimitrisAlivas/StarQE): StarQE
- [SMORE](https://github.com/google-research/smore): GQE, Query2Box, BetaE + Very Large Datasets
- [GNN-QE](https://github.com/DeepGraphLearning/GNN-QE): GNN-QE
- [TAR](https://github.com/lilv98/TAR): Former ABIN


## All Papers (31)

<details>
  <summary>Click to expand </summary>

  1. (GQE) [Embedding Logical Queries on Knowledge Graphs](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf) NeurIPS 2018
  2. (GQE + hashing) [Learning to Hash for Efficient Search over Incomplete Knowledge Graphs](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA) ICDM’19
  3. (Query2Box) [Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings](https://openreview.net/pdf?id=BJgr4kSFDS) ICLR 2020
  4. (BetaE) [Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf) NeurIPS 2020
  5. (EmQL) [Faithful embeddings for knowledge base queries](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html) NeurIPS 2020
  6. (MPQE) [Message Passing Query Embedding](https://grlplus.github.io/papers/26.pdf) ICML’20 Workshop
  7. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480) AKBC’21
  8. (BiQE) [Answering complex queries in knowledge graphs with bidirectional sequence encoders](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI’21 
  9. [Approximate knowledge graph query answering: from ranking to binary classification](https://library.oapen.org/bitstream/handle/20.500.12657/48251/9783030723088.pdf?sequence=1#page=114) ← benchmarking, 2020 / 2021
  10. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf) arxiv, BetaE datasets, 2021
  11. (ConE) [Cone: Cone embeddings for multi-hop reasoning over knowledge graphs](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html) NeurIPS’21
  12. (PERM) [Probabilistic entity representation model for reasoning over knowledge graphs](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html) (improv over BetaE) NeurIPS’21
  13. (CQD) [Complex Query Answering with Neural Link Predictors](https://openreview.net/forum?id=Mos9F9kDwkz) ICLR’21
  14. (HypE) [Self-Supervised Hyperboloid Representations from Logical Queries over Knowledge Graphs](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021 + (new) DBpedia + Amazon prod dataset
  15. (NewLook) [Neural-Answering Logical Queries on Knowledge Graphs](http://tonghanghang.org/pdfs/kdd21_newlook.pdf) (KDD’21) ← subgraph matching
  16. [Benchmarking the Combinatorial Generalizability of Complex Query Answering on Knowledge Graphs](https://arxiv.org/abs/2109.08925) ← benchmarking, 2021, new datasets
  17. [A Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf) arxiv 2021 (Q2B with rules), new datasets with types - LUBM + NELL
  18. (LogicE) [Logic Embeddings for Complex Query Answering](https://arxiv.org/pdf/2103.00418.pdf) arxiv 2021
  19. (StarQE) [Query Embedding on Hyper-relational Knowledge Graphs](https://arxiv.org/abs/2106.08166) ICLR 2022, new datasets
  20. (MLPMix) [Neural Methods for Logical Reasoning over Knowledge Graphs](https://openreview.net/forum?id=tgcAoUVHRIB) ICLR 2022
  21. (FuzzQE) [Fuzzy Logic Based Logical Query Answering on Knowledge Graphs](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  22. (GNN-QE)  [Neural-Symbolic Models for Logical Queries on Knowledge Graphs](https://arxiv.org/abs/2205.10128), ICML 2022
  23. (CBR-SUBG) [Knowledge base question answering by case-based reasoning over subgraphs](https://proceedings.mlr.press/v162/das22a.html) ICML 2022 ← entailment only, custom datasets
  24. (SMORE) [SMORE: Knowledge Graph Completion and Multi-hop Reasoning in Massive Knowledge Graphs](https://arxiv.org/abs/2110.14890) KDD 2022 ← very large graphs, new datasets
  25. (kgTransformer) [Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex Logical Queries](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf) KDD 2022, old Q2B datasets
  26. (Query2Particles) [Query2Particles: Knowledge Graph Reasoning with Particle Embeddings](https://arxiv.org/abs/2204.12847), Findings NAACL’22
  27. (TAR) [Joint Abductive and Inductive Neural Logical Reasoning](https://arxiv.org/abs/2205.14591) (arxiv, 2022) Class Hierarchy, new dataset
  28. (TeMP) [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782) (arxiv 2022) Class Hierarchy, new dataset
  29. (FLEX) [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039) (arxiv 2022)
  30. (TFLEX) [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf) (arxiv, 2022), new dataset
  31. (LinE) [LinE: Logical Query Reasoning over Hierarchical Knowledge Graphs](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw) KDD 2022

</details>