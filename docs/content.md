layout: true
  
<div class="my-header"></div>

<div class="my-footer">
  <table>
    <tr>
      <td>Digitales Wörterbuch der Deutschen Sprache</td>
      <td style="text-align:right"><a href="https://www.dwds.de/">www.dwds.de</a></td>
    </tr>
  </table>
</div>

---

class: title-slide

# e-Lexicography

## Techniques and tools for automatic corpus annotation

| Alexander Geyken | Sebastian Göttel | Kay-Michael Würzner |
|:----------------:|:----------------:|:-------------------:|
| [geyken@bbaw.de](mailto:geyken@bbaw.de) | [sebastian.goettel@bbaw.de](mailto:sebastian.goettel@bbaw.de) | [wuerzner@bbaw.de](mailto:wuerzner@bbaw.de) |

---

class: title-slide

# Text corpora

---

# Text corpora

- Collections of texts
- *linguistic* reference corpora
    + *representative* with respect to a language as a whole (or a certain historical form)
        * English: British National Corpus (Burnard, 1995)
        * German: Deutsches Textarchiv (Geyken and Klein, 2009)
- *special* corpora
    + *representative* sample of a language with respect to
        * medium: news paper, (movie) subtitles, internet blogs ...
        * content: infant, youth speech ...
        * research: Penn Treebank (Marcus et al., 1993), childLex (Schroeder et al., 2014)

---

# Corpora and lexicography

- Guidance and knowledge for the lexicographer
- Means of evidence
    + Importance (“Is word *x* frequent enough for my dictionary?”)
    + Grammar (“Does word *x* have a plural?”)
    + Semantics (“Does word *x* have multiple meanings?”)
    + Pragmatics (“Is word *x* a terminus technicus?”)
- Challenge: Corpora are huge! How do we find interesting word occurrences?
- Approach: Abstraction through grouping of tokens

---

class: title-slide

# Linguistic annotation

---

# Linguistic annotation

- In the dark ages of *Zettelkästen*: Manual reading and evaluation of text sources
- Not feasible for modern-size corpora: Automatic analysis tool chain
- Annotation of linguistic features as a preprocessing step
    + Easier to search through
    + Easier to identify relevant corpus records
    + Easier to perform quantitative analyses
- With respect to different levels of representation:
    + *Word*: Syllable structure, morphological segmentation, lexical semantics
    + *Word group*: Multi-word expressions, collocations, named entities
    + *Phrases*: Syntactical category and function
    + *Sentence*: Syntactical structure, semantics, textual function

---

# Linguistic annotation

- A sample tool chain:
