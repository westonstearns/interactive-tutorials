Tutorial
--------

Lists are very similar to arrays. They can contain any type of variable, and they can contain as many variables as you wish. Lists can also be iterated over in a very simple manner. Here is an example of how to build a list.

<div data-datacamp-exercise="" data-height="300" data-encoded="true">
eyJsYW5ndWFnZSI6InB5dGhvbiIsInByZV9leGVyY2lzZV9jb2RlIjoiIiwic2FtcGxlIjoibXlsaXN0ID0gW11cbm15bGlzdC5hcHBlbmQoMSlcbm15bGlzdC5hcHBlbmQoMilcbm15bGlzdC5hcHBlbmQoMylcbnByaW50KG15bGlzdFswXSkgIyBwcmludHMgMVxucHJpbnQobXlsaXN0WzFdKSAjIHByaW50cyAyXG5wcmludChteWxpc3RbMl0pICMgcHJpbnRzIDNcblxuIyBwcmludHMgb3V0IDEsMiwzXG5mb3IgeCBpbiBteWxpc3Q6XG4gIHByaW50KHgpXG4iLCJzb2x1dGlvbiI6IiIsInNjdCI6IiJ9
</div>

Accessing an index which does not exist generates an exception (an error).

<div data-datacamp-exercise="" data-height="200" data-encoded="true">
eyJsYW5ndWFnZSI6InB5dGhvbiIsInByZV9leGVyY2lzZV9jb2RlIjoiIiwic2FtcGxlIjoibXlsaXN0ID0gWzEsMiwzXVxucHJpbnQobXlsaXN0WzEwXSlcbiIsInNvbHV0aW9uIjoiIiwic2N0IjoiIn0=
</div>

Exercise
--------

In this exercise, you will need to add numbers and strings to the correct lists using the "append" list method. You must add the numbers 1,2, and 3 to the "numbers" list, and the words 'hello' and 'world' to the strings variable. 

You will also have to fill in the variable second_name with the second name in the names list, using the brackets operator `[]`. Note that the index is zero-based, so if you want to access the second item in the list, its index will be 1.

<div data-datacamp-exercise="" data-height="300" data-encoded="true">
eyJsYW5ndWFnZSI6InB5dGhvbiIsInByZV9leGVyY2lzZV9jb2RlIjoiIiwic2FtcGxlIjoiI1R1dG9yaWFsIGNvZGVcbm51bWJlcnMgPSBbXVxuc3RyaW5ncyA9IFtdXG5uYW1lcyA9IFtcIkpvaG5cIiwgXCJFcmljXCIsIFwiSmVzc2ljYVwiXVxuXG4jIHdyaXRlIHlvdXIgY29kZSBoZXJlXG5zZWNvbmRfbmFtZSA9IE5vbmVcblxuXG4jIHRoaXMgY29kZSBzaG91bGQgd3JpdGUgb3V0IHRoZSBmaWxsZWQgYXJyYXlzIGFuZCB0aGUgc2Vjb25kIG5hbWUgaW4gdGhlIG5hbWVzIGxpc3QgKEVyaWMpLlxucHJpbnQobnVtYmVycylcbnByaW50KHN0cmluZ3MpXG5wcmludChcIlRoZSBzZWNvbmQgbmFtZSBvbiB0aGUgbmFtZXMgbGlzdCBpcyAlc1wiICUgc2Vjb25kX25hbWUpXG4iLCJzb2x1dGlvbiI6Im51bWJlcnMgPSBbXVxuc3RyaW5ncyA9IFtdXG5uYW1lcyA9IFtcIkpvaG5cIiwgXCJFcmljXCIsIFwiSmVzc2ljYVwiXVxuXG4jIHdyaXRlIHlvdXIgY29kZSBoZXJlXG5udW1iZXJzLmFwcGVuZCgxKVxubnVtYmVycy5hcHBlbmQoMilcbm51bWJlcnMuYXBwZW5kKDMpXG5cbnN0cmluZ3MuYXBwZW5kKFwiaGVsbG9cIilcbnN0cmluZ3MuYXBwZW5kKFwid29ybGRcIilcblxuc2Vjb25kX25hbWUgPSBuYW1lc1sxXVxuXG4jIHRoaXMgY29kZSBzaG91bGQgd3JpdGUgb3V0IHRoZSBmaWxsZWQgYXJyYXlzIGFuZCB0aGUgc2Vjb25kIG5hbWUgaW4gdGhlIG5hbWVzIGxpc3QgKEVyaWMpLlxucHJpbnQobnVtYmVycylcbnByaW50KHN0cmluZ3MpXG5wcmludChcIlRoZSBzZWNvbmQgbmFtZSBvbiB0aGUgbmFtZXMgbGlzdCBpcyAlc1wiICUgc2Vjb25kX25hbWUpXG4iLCJzY3QiOiJ0ZXN0X291dHB1dF9jb250YWlucyhcIlsxLDIsM11cIiwgbm9fb3V0cHV0X21zZz0gXCJNYWtlIHN1cmUgdGhhdCB5b3UgaGF2ZSBwcmludGVkIHRoZSBgbnVtYmVyc2AgbGlzdC5cIilcbnRlc3Rfb3V0cHV0X2NvbnRhaW5zKFwiWydoZWxsbycsICd3b3JsZCddXCIsIG5vX291dHB1dF9tc2c9IFwiTWFrZSBzdXJlIHRoYXQgeW91IGhhdmUgcHJpbnRlZCB0aGUgYHN0cmluZ3NgIGxpc3QuXCIpXG50ZXN0X291dHB1dF9jb250YWlucyhcIlRoZSBzZWNvbmQgbmFtZSBvbiB0aGUgbmFtZXMgbGlzdCBpcyBFcmljXCIsIG5vX291dHB1dF9tc2c9IFwiRGlkIHlvdSBmaWxsIGluIHRoZSB2YXJpYWJsZSBgc2Vjb25kX25hbWVgIHdpdGggdGhlIHNlY29uZCBuYW1lIGluIHRoZSBuYW1lcyBsaXN0P1wiKVxuc3VjY2Vzc19tc2coXCJHcmVhdCBKb2IhXCIpIn0=
</div>
