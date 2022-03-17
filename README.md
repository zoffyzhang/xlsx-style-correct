this package is forked from <https://github.com/luizotavioautomacao/xlsx-style-correct>, but delete all the dependencies that cause Node.js engine version incompatible problem when installing the package.

# pacote original -> "xlsx-style": "^0.8.13"

# xlsx-style

# About this fork

**NOTE:** [This project](https://github.com/luizotavioautomacao/xlsx-style-correct) is a fork of the original [xlsx-style](https://www.npmjs.com/package/xlsx-style) project.

# Goal

Fix the problem:
ERROR in ./node_modules/xlsx-style/dist/cpexcel.js
Module not found: Error: Can't resolve './cptable' in '/opt/build/repo/node_modules/xlsx-style/dist'

## Installation

With [npm](https://www.npmjs.org/package/xlsx-style-correct):

```sh
npm install xlsx-style-correct --save
```

### Supported formats

Supported read formats:

- Excel 2007+ XML Formats (XLSX/XLSM)
- Excel 2007+ Binary Format (XLSB)
- Excel 2003-2004 XML Format (XML "SpreadsheetML")
- Excel 97-2004 (XLS BIFF8)
- Excel 5.0/95 (XLS BIFF5)
- OpenDocument Spreadsheet (ODS)

Supported write formats:

- XLSX
- CSV (and general DSV)
- JSON and JS objects (various styles)

Demo: <http://oss.sheetjs.com/js-xlsx>

Source: <http://git.io/xlsx>
