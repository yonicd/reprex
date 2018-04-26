Tests and Coverage
================
26 April, 2018 16:07:38

-   [Coverage](#coverage)
-   [Unit Tests](#unit-tests)

Coverage
--------

Coverage summary is created using the [covr](https://github.com/r-lib/covr) package.

| Object                                                   | Coverage (%) |
|:---------------------------------------------------------|:------------:|
| reprex                                                   |     81.82    |
| [R/zzz.R](../R/zzz.R)                                    |     0.00     |
| [R/whisker.R](../R/whisker.R)                            |     33.33    |
| [R/utils-interactivity.R](../R/utils-interactivity.R)    |     62.50    |
| [R/filepaths.R](../R/filepaths.R)                        |     80.36    |
| [R/reprex.R](../R/reprex.R)                              |     80.71    |
| [R/ensure.R](../R/ensure.R)                              |     82.76    |
| [R/optionally.R](../R/optionally.R)                      |     88.89    |
| [R/utils.R](../R/utils.R)                                |     94.92    |
| [R/reprex-undo.R](../R/reprex-undo.R)                    |     97.18    |
| [R/stringify\_expression.R](../R/stringify_expression.R) |    100.00    |

<br>

Unit Tests
----------

Unit Test summary is created using the [testthat](https://github.com/r-lib/testthat) package.

| file                                                                |    n|   time|  error|  failed|  skipped|  warning|
|:--------------------------------------------------------------------|----:|------:|------:|-------:|--------:|--------:|
| [test-env.R](testthat/test-env.R)                                   |    5|  3.549|      0|       0|        0|        0|
| [test-input.R](testthat/test-input.R)                               |   14|  1.856|      0|       0|        0|        0|
| [test-knitr-options.R](testthat/test-knitr-options.R)               |    5|  3.388|      0|       0|        0|        0|
| [test-optionally.R](testthat/test-optionally.R)                     |    5|  0.705|      0|       0|        0|        0|
| [test-outfiles.R](testthat/test-outfiles.R)                         |   19|  5.586|      0|       0|        0|        0|
| [test-pandoc.R](testthat/test-pandoc.R)                             |    3|  1.499|      0|       0|        0|        0|
| [test-reprex.R](testthat/test-reprex.R)                             |    2|  1.377|      0|       0|        0|        0|
| [test-session-info.R](testthat/test-session-info.R)                 |    5|  0.066|      0|       0|        0|        0|
| [test-stdout-stderr.R](testthat/test-stdout-stderr.R)               |    5|  2.420|      0|       0|        0|        0|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) |   10|  0.019|      0|       0|        0|        0|
| [test-styler.R](testthat/test-styler.R)                             |    2|  0.496|      0|       0|        0|        0|
| [test-tidyverse.R](testthat/test-tidyverse.R)                       |    3|  5.996|      0|       0|        0|        0|
| [test-undo.R](testthat/test-undo.R)                                 |   10|  5.232|      0|       0|        0|        0|
| [test-utils.R](testthat/test-utils.R)                               |    2|  0.004|      0|       0|        0|        0|
| [test-venues.R](testthat/test-venues.R)                             |    6|  5.393|      0|       0|        0|        0|

| file                                                                | test                                                            | context                    | status |    n|   time|
|:--------------------------------------------------------------------|:----------------------------------------------------------------|:---------------------------|:-------|----:|------:|
| [test-env.R](testthat/test-env.R)                                   | can't see environment of caller                                 | environments               | PASS   |    1|  0.665|
| [test-env.R](testthat/test-env.R)                                   | reprex doesn't write into environment of caller                 | environments               | PASS   |    3|  2.211|
| [test-env.R](testthat/test-env.R)                                   | I understand exactly what I'm putting in reprex env             | environments               | PASS   |    1|  0.673|
| [test-input.R](testthat/test-input.R)                               | reprex: clipboard input works                                   | input                      | PASS   |    1|  0.308|
| [test-input.R](testthat/test-input.R)                               | reprex: expression input works                                  | input                      | PASS   |    1|  0.022|
| [test-input.R](testthat/test-input.R)                               | reprex: character input works                                   | input                      | PASS   |    1|  0.024|
| [test-input.R](testthat/test-input.R)                               | reprex: file input works                                        | input                      | PASS   |    1|  0.024|
| [test-input.R](testthat/test-input.R)                               | reprex: file input in a subdirectory works                      | input                      | PASS   |    1|  0.020|
| [test-input.R](testthat/test-input.R)                               | Circular use is detected before source file written             | input                      | PASS   |    2|  1.372|
| [test-input.R](testthat/test-input.R)                               | Leading prompts are removed                                     | input                      | PASS   |    2|  0.040|
| [test-input.R](testthat/test-input.R)                               | ingest\_input() works                                           | input                      | PASS   |    3|  0.011|
| [test-input.R](testthat/test-input.R)                               | newlines in code are protected and uniformly so across venues   | input                      | PASS   |    2|  0.035|
| [test-knitr-options.R](testthat/test-knitr-options.R)               | chunk options can be overridden                                 | knitr options              | PASS   |    1|  1.324|
| [test-knitr-options.R](testthat/test-knitr-options.R)               | `comment` is special                                            | knitr options              | PASS   |    2|  2.036|
| [test-knitr-options.R](testthat/test-knitr-options.R)               | venue determines default value of `upload.fun`                  | knitr options              | PASS   |    2|  0.028|
| [test-optionally.R](testthat/test-optionally.R)                     | `si` can be set via option                                      | optionally                 | PASS   |    1|  0.013|
| [test-optionally.R](testthat/test-optionally.R)                     | `advertise` can be set via option                               | optionally                 | PASS   |    1|  0.011|
| [test-optionally.R](testthat/test-optionally.R)                     | `comment` can be set via option                                 | optionally                 | PASS   |    1|  0.650|
| [test-optionally.R](testthat/test-optionally.R)                     | `tidyverse_quiet` can be set via option                         | optionally                 | PASS   |    1|  0.018|
| [test-optionally.R](testthat/test-optionally.R)                     | `std_out_err` can be set via option                             | optionally                 | PASS   |    1|  0.013|
| [test-outfiles.R](testthat/test-outfiles.R)                         | expected outfiles are written and messaged, venue = 'gh'        | outfiles                   | PASS   |    3|  0.683|
| [test-outfiles.R](testthat/test-outfiles.R)                         | expected outfiles are written and messaged, venue = 'R'         | outfiles                   | PASS   |    5|  0.672|
| [test-outfiles.R](testthat/test-outfiles.R)                         | `.md` extension is stripped from outfile                        | outfiles                   | PASS   |    2|  0.653|
| [test-outfiles.R](testthat/test-outfiles.R)                         | .R outfile doesn't clobber .R infile                            | outfiles                   | PASS   |    1|  0.702|
| [test-outfiles.R](testthat/test-outfiles.R)                         | outfiles in a subdirectory works                                | outfiles                   | PASS   |    1|  0.779|
| [test-outfiles.R](testthat/test-outfiles.R)                         | outfiles based on input file                                    | outfiles                   | PASS   |    2|  0.684|
| [test-outfiles.R](testthat/test-outfiles.R)                         | outfiles based on tempfile()                                    | outfiles                   | PASS   |    3|  0.701|
| [test-outfiles.R](testthat/test-outfiles.R)                         | pre-existing foo\_reprex.R doesn't get clobbered w/o user's OK  | outfiles                   | PASS   |    2|  0.712|
| [test-pandoc.R](testthat/test-pandoc.R)                             | pandoc does not add hard linebreak in the ad                    | pandoc                     | PASS   |    2|  1.496|
| [test-pandoc.R](testthat/test-pandoc.R)                             | pandoc version checkers don't error                             | pandoc                     | PASS   |    1|  0.003|
| [test-reprex.R](testthat/test-reprex.R)                             | keep.source is TRUE inside the reprex()                         | reprex                     | PASS   |    1|  0.697|
| [test-reprex.R](testthat/test-reprex.R)                             | reprex() works with code that deals with srcrefs                | reprex                     | PASS   |    1|  0.680|
| [test-session-info.R](testthat/test-session-info.R)                 | session info is omitted / included                              | session info               | PASS   |    3|  0.053|
| [test-session-info.R](testthat/test-session-info.R)                 | session info is folded on github                                | session info               | PASS   |    2|  0.013|
| [test-stdout-stderr.R](testthat/test-stdout-stderr.R)               | stdout is captured                                              | stdout-stderr              | PASS   |    2|  1.078|
| [test-stdout-stderr.R](testthat/test-stdout-stderr.R)               | stdout placeholder appears if nothing is captured               | stdout-stderr              | PASS   |    2|  0.666|
| [test-stdout-stderr.R](testthat/test-stdout-stderr.R)               | stdout placeholder is absent if explicitly excluded             | stdout-stderr              | PASS   |    1|  0.676|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) | simple statements are stringified                               | expression stringification | PASS   |    3|  0.005|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) | one statement, brackets, multiple lines, take 1                 | expression stringification | PASS   |    1|  0.002|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) | one statement, brackets, multiple lines, take 2                 | expression stringification | PASS   |    1|  0.002|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) | one statement, brackets, multiple lines, take 3                 | expression stringification | PASS   |    1|  0.003|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) | multiple statements, brackets, semicolon                        | expression stringification | PASS   |    1|  0.002|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) | leading, embedded, trailing comment, \#89                       | expression stringification | PASS   |    1|  0.002|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) | trailing inline comment, \#91                                   | expression stringification | PASS   |    1|  0.002|
| [test-stringify-expression.R](testthat/test-stringify-expression.R) | trailing inline comment AND trailing comment line               | expression stringification | PASS   |    1|  0.001|
| [test-styler.R](testthat/test-styler.R)                             | ugly code gets restyled                                         | style                      | PASS   |    1|  0.191|
| [test-styler.R](testthat/test-styler.R)                             | bang bang bang is not mangled with parentheses                  | style                      | PASS   |    1|  0.305|
| [test-tidyverse.R](testthat/test-tidyverse.R)                       | reprex() suppresses tidyverse startup message by default        | tidyverse                  | PASS   |    1|  2.379|
| [test-tidyverse.R](testthat/test-tidyverse.R)                       | reprex() has control over tidyverse startup message             | tidyverse                  | PASS   |    2|  3.617|
| [test-undo.R](testthat/test-undo.R)                                 | round trip, venue = 'gh': reprex() --&gt; reprex\_invert()      | undo                       | PASS   |    1|  0.830|
| [test-undo.R](testthat/test-undo.R)                                 | round trip, venue = 'so': reprex() --&gt; reprex\_invert()      | undo                       | PASS   |    1|  0.794|
| [test-undo.R](testthat/test-undo.R)                                 | round trip, venue = 'r': reprex() --&gt; reprex\_invert()       | undo                       | PASS   |    1|  0.792|
| [test-undo.R](testthat/test-undo.R)                                 | reprex\_rescue() rescues code from R Console copy/paste         | undo                       | PASS   |    1|  0.088|
| [test-undo.R](testthat/test-undo.R)                                 | reprex\_rescue()'s prompt argument works                        | undo                       | PASS   |    1|  0.089|
| [test-undo.R](testthat/test-undo.R)                                 | reprex\_rescue()'s continue argument works                      | undo                       | PASS   |    1|  0.090|
| [test-undo.R](testthat/test-undo.R)                                 | reprex\_rescue() can cope with leading whitespace               | undo                       | PASS   |    1|  0.091|
| [test-undo.R](testthat/test-undo.R)                                 | reprex\_invert() can write to specific outfile                  | undo                       | PASS   |    1|  0.757|
| [test-undo.R](testthat/test-undo.R)                                 | reprex\_invert() can name its own outfile                       | undo                       | PASS   |    1|  0.854|
| [test-undo.R](testthat/test-undo.R)                                 | reprex\_invert() can name outfile based on input filepath       | undo                       | PASS   |    1|  0.847|
| [test-utils.R](testthat/test-utils.R)                               | nope() defaults to 'yes' if user not available                  | utils                      | PASS   |    1|  0.002|
| [test-utils.R](testthat/test-utils.R)                               | yep() defaults to 'no' if user not available                    | utils                      | PASS   |    1|  0.002|
| [test-venues.R](testthat/test-venues.R)                             | venue = 'so' works with/without leading prose                   | venues                     | PASS   |    2|  1.326|
| [test-venues.R](testthat/test-venues.R)                             | venue = 'R' works, regardless of case                           | venues                     | PASS   |    2|  1.364|
| [test-venues.R](testthat/test-venues.R)                             | venue = 'ds' is an alias for 'gh'                               | venues                     | PASS   |    1|  1.988|
| [test-venues.R](testthat/test-venues.R)                             | local image link is not interrupted by hard line break for 'gh' | venues                     | PASS   |    1|  0.715|
