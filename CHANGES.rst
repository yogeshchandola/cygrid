2.0 (unreleased)
=======================

- Major overhaul of the handling of array shapes. No need to manually
  fiddle with FITS headers (`NAXIS3` key) anymore. `cygrid` will now do
  everything automatically behind the curtain. [#12]

1.0.2 (unreleased, bugfix release)
==================================

Bugfixes
~~~~~~~~~~


1.0.1 (2019-01-19)
=======================

Packaging/Installation
~~~~~~~~~~~~~~~~~~~~~~
- Use clang/LLVM for the compilation on MacOS and use this path to generate
  MacOS binary wheels for PyPI. #5b32

Documentation
~~~~~~~~~~~~~
- Add bibtex item to README. #74c7
- Fix some URLs in the documention. #a42b


1.0.0 (2019-01-18)
=======================

Other
-----
- Add a user manual to supplement the existing tutorial notebooks.
- Now using Astropy package template.
