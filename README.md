# refseq63m — MITOS2 reference data (RefSeq 63 Metazoa)

A mirror of `refseq63m.tar.bz2` from the MITOS2 reference data, Zenodo record
[4284483](https://zenodo.org/records/4284483) (doi:[10.5281/zenodo.4284483](https://doi.org/10.5281/zenodo.4284483)),
byte for byte (md5 `fb3bc018821456d82805be9d966cfc61`, the same as Zenodo's). It is mirrored here only because Zenodo throttles
downloads; MitOmics downloads it from this repository and falls back to Zenodo.

    wget https://raw.githubusercontent.com/zampini28/refseq63m/refs/heads/main/refseq63m.tar.bz2
    echo "fb3bc018821456d82805be9d966cfc61  refseq63m.tar.bz2" | md5sum -c -
    tar xjf refseq63m.tar.bz2          # -> refseq63m/, used as: runmitos ... -r refseq63m -R .

**Authors:** Matthias Bernt, Frank Jühling, Alexander Donath, Abdullah H. Sahyoun, Manja Marz,
Peter F. Stadler, Martin Middendorf. *Reference data for MITOS2.* Zenodo (2020).

**License:** [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by-4.0/),
as published on Zenodo. Unmodified.
