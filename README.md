ePUB-Converter
==============

This is the source code of android application called ePUB converter

Credits to Ezio Querini
Its originally from this source https://sourceforge.net/p/epubator/home/Home/

ePUBator extract text from a PDF file and put it in a well formed (epubcheck compliant) ePUB file.

PDF extraction based on iText library <http://itextpdf.com/> released under the AGPL license. 

- ePUBator IS MADE FOR BOOKS, NOT FOR EVERY TYPE OF PDF (DON'T ASK IT TOO MUCH).
- ePUBator doesn't need internet connection (doesn't send your docs somewhere on the net, doesn't have ads).
- ePUBator extract text (no text from pictures or from raster PDF).
- ePUBator try to extract images (only png, jpg and gif) but puts them at the page's end.
- ePUBator try to extract the table of contents if present (or creates a dummy TOC).
- ePUBator doesn't extract the font size and style.
- ePUBator save the ePUB file in the same folder of PDF file (it uses the PDF filename to generate ePUB filename and the title in the frontpage, so rename the PDF before conversion).
- ePUBator works fine only with single column PDF (worse with multi column or tables).
- ePUBator can fail extraction (5 of 358 books with v0.8.1 on my Atrix).
