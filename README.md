# Citation-Style-Manager

In scientific publications, a reference to a previous work (source) that is discussed in the manuscript is called a citation. In different scientific disciplines, and sometimes even different journals, different so-called citation styles are used. The citation style defines how a citation is formatted. We will consider two different citation styles in this question:
- APA style: citation style of the American Psychological Association (https://www.mendeley.com/guides/apa-citation-guide), see also Wikipedia page (https://en.wikipedia.org/wiki/APA_style). This style is widely used in Psychology and Social Sciences.
- IEEE: citation style of the Institute for Electrical and Electronics Engineers (IEEE) is used in IEEE journals which cover engineering and related disciplines (https://pitt.libguides.com/citationhelp/ieee). See the Learning Materials/Coursework folder on Learning Central for more information on the IEEE style.

There are two main aspects to a publication where citation styles apply:
1. In-text citations: These are used in the text body whenever one refers to, summarises,
paraphrases, or quotes from another source. This is an example from Wikipedia
(https://en.wikipedia.org/wiki/APA_style) for a sentence including an in-text citation
of a paper by Schmidt and Oh in APA format:

In our postfactual era, many members of the public fear that the findings of
science are not real (Schmidt & Oh, 2016).

In IEEE format, references are given as numbers in square brackets. Example:
This is compounded by the fact that the field is evolving from work performed
by an individual that does data science to a team that does data science [1].

2. Reference list: In a scientific publication, the last section is typically the References
section, which provides full details on the in-text citations. For instance, the full
reference corresponding to the Schmidt & Oh (2016) in-text citation above would be:

Schmidt, F. L., & Oh, I.-S. (2016). The crisis of confidence in research
findings in psychology: Is lack of replication the real problem? Or is it
something else? Archives of Scientific Psychology, 4(1), 32–37.
https://doi.org/10.1037/arc0000029

In an article using IEEE format, every reference in the reference list needs to be
numbered:

1. J. Saltz, "The Need for New Processes Methodologies and Tools to Support
Big Data Teams and Improve Big Data Project Effectiveness", Big Data
Conference, 2015.

Implement a function change_style(filepath, style), which takes as input two arguments: (1) filepath, which can be either IEEEexample.docx or APAexample.docx and (2) style (a string being either IEEE or APA), and swaps their citation style (i.e., converts IEEE citations into APA and vice versa).
After conversion, save the file by appending ‘_APA_style’ or ‘_IEEE_style’ to the filename (e.g. ‘myfile_IEEE_style.docx’).
