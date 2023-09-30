---
layout: article
title: Post Quantum Cryptography
sidebar:
  nav: docs-en
---
## Supersingular Isogney
* **Supersingular Isogeny-Based Single Compression Cryptographic Hash Function**: The paper is accepted in *2023 IEEE Global Communications Conference: Communication & Information Systems Security*. In this paper we discuss about.
  * *Novel Single Compression Hash Function*: Introducing an innovative single compression cryptographic hash function.
  * *Supersingular Isogeny Foundation*: Built upon the traversal of the supersingular isogeny (2-isogeny) graph and point mapping under isogeny.
  * *Enhanced Security*: Unlike existing approaches, the proposed function conceals the curve's j-invariant, posing two formidable challenges to attackers: identifying the curve from its X-coordinate and solving the supersingular isogeny problem.
  * *Improved Preimage Resistance*: Significantly bolstered preimage resistance.
  * *Collision-Free Assurance*: The function inherently ensures a collision-free property through the random mapping of different points or isogenies to the same point.
  * *Efficient Processing*: The compression function efficiently processes bits from multiple message blocks in a single step, reducing computational complexity.
  * *Parallelization Resilience*: Organically modifies the message to resist parallelization attempts.
  * *Comparative Analysis*: In-depth computational complexity analysis compared to CGL and CGL-like hash functions.
* <a id="raw-url" href="https://link.springer.com/chapter/10.1007/978-3-031-27041-3_2">
**Implementation Aspects of Supersingular Isogeny-Based Cryptographic Hash Function**</a>: The paper accepted and presented in *International Wireless Internet Conference WiCON 2022*. The snippets of the paper is:
  * CGL Hash Function: Charles, Goren, and Lauter introduced the CGL hash function, which leverages the traversal of a supersingular isogeny graph (expander graph).
  * Compact Variant Study: This paper conducts an in-depth exploration of the compact variation of the standard CGL hash function. The study involves utilizing various forms of elliptic curves, including Weierstrass, Montgomery, and Legendre.
  * Reducing Redundancy: The research reveals opportunities to eliminate redundant computations present in the original CGL hash function proposals by harnessing the unique characteristics of different elliptic curve forms.
  * Experimental Comparison: The study includes experiments to compare the running time and total number of collisions among the implemented algorithms, providing insights into their practical performance.
