# Phpstorm Live Templates Twig OctoberCMS (Archived: OctoberCMS is totally dead because of greediness)

## References

- [OctoberCMS Documentation](https://octobercms.com/docs/cms/themes)
- [BarrelStrength Twig Live Templates](https://github.com/barrelstrength/PhpStorm-Live-Templates-Twig-Extended) : Refer here for installation

## Common Boilerplate

| Abbreviation | Description | Code Generated |
|--|--|--|
| `!ph`  | Inject to placeholder variable |`{% put ... %} ... {% endput %}`|
|`!phd`|Inject to placeholder variable and default|`{% put ... %} ... {% endput %}`|
|`!scripts`|Inject to scripts|`{% put scripts %} <script> ... </scripts> {% endput %}`|
|`!styles`|Inject to styles|`{% put styles%} <style> ... </style> {% endput %}`|
|`comp`|Generate component block|`{% component '...' %}`|
|`content`|Generate content block|`{% content '...' %}`|
|`dump` |Generate dump block|`{{ dump(...) }}`|
|`fajax`|Generate form_ajax block|`{{ form_ajax() }}`|
|`fclose` |Generate form_close block|`{{ form_close() }}`|
|`flash` |Generate flash block|`{% flash %}...{% endflash %}`|
|`fopen`||`{{ form_open() }}`|
|`for`||`{% for ... in ... %} ... {% endfor %}`|
|`fore`||`{% for ... in ... %} ... {% else %} ... {% endfor %}`|
|`hc`||`{{ html_clean('...') }}`|
|`he`||`{{ html_email('...') }}`|
|`hl`||`{{ html_limit('...') }}`|
|`hs`||`{{ html_strip('...') }}`|
|`if`|Generate if block|`{% if ... %} ... {% endif %}`|
|`ife`|Generate if else block|`{% if ... %} ... {% else %} ... {% endif %}`|
|`ifs`|Generate if else shorthand|`{{ ... ? '...' : '...' }}`|
|`macro`||`{% macro var1(...) %} ... {% endmacro var1 %}`|
|`page`||`{% page %}`|
|`partial`||`{% partial '...' %}`|
|`ph`||`{% placeholder ... %}`|
|`phd`||`{% placeholder ... default %} ... {% endplaceholder %}`|
|`scripts`||`{% scripts %}`|
|`strc`||`{{ str_camel(...) }}`|
|`strl`||`{{ str_limit(...) }}`|
|`strpl`||`{{ str_plural(...) }}`|
|`strsn`||`{{ str_snake(...) }}`|
|`strsn2`||`{{ str_snake(...), '...' }}`|
|`strst`||`{{ str_studly(...) }}`|
|`strw`||`{{ str_words(...) }}`|
|`styles`||`{% styles %}`|
|`tc`||`{{ this.controller.var }}`|
|`te`||`{{ this.environment.var }}`|
|`tl`||`{{ this.layout.var }}`|
|`tpg`||`{{ this.page.var }}`|
|`tpr`||`{{ this.param.var }}`|
|`ts`||`{{ this.session.var }}`|
|`tt`||`{{ this.theme.var }}`|
|`verb`||`{% verbatim %} ... {% endverbatim %}`|
|&#124;`app`||`{{ '...'` &#124; `app }}`|
|&#124;`d`||`{{ '...'` &#124; `default }}`|
|&#124;`ih`||`{{ '...'` &#124; `imageHeight }}`|
|&#124;`iw`||`{{ '...'` &#124; `imageWidth }}`|
|&#124;`md`||`{{ '...'` &#124; `md }}`|
|&#124;`m`||`{{ '...'` &#124; `media }}`|
|&#124;`p`||`{{ '...'` &#124; `page }}`|
|&#124;`raw`||`{{ '...'` &#124; `raw }}`|
|&#124;`rs`||`{{ '...'` &#124; `resize }}`|
|&#124;`th`||`{{ '...'` &#124; `theme }}`|

## Additional Boilerplate

| Abbreviation | Description |
|--|--|
| `~html` | HTML boilerplate + meta + combine CSS & JS |
| `cc` | Combine CSS file |
| `cj` | Combine JS file |
