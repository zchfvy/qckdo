========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/qckdo/badge/?style=flat
    :target: https://readthedocs.org/projects/qckdo
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/zchfvy/qckdo.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/zchfvy/qckdo

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/zchfvy/qckdo?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/zchfvy/qckdo

.. |requires| image:: https://requires.io/github/zchfvy/qckdo/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/zchfvy/qckdo/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/zchfvy/qckdo/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/zchfvy/qckdo

.. |version| image:: https://img.shields.io/pypi/v/qckdo.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/qckdo

.. |downloads| image:: https://img.shields.io/pypi/dm/qckdo.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/qckdo

.. |wheel| image:: https://img.shields.io/pypi/wheel/qckdo.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/qckdo

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/qckdo.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/qckdo

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/qckdo.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/qckdo


.. end-badges

Quickly run common command-line tasks, without having to memorize the commands.

* Free software: BSD license

Installation
============

::

    pip install qckdo

Documentation
=============

https://qckdo.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
