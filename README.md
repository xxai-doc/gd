<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

Thathas a’ moladh nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) a stàladh an toiseach, agus an uairsin `direnv allow` às deidh dhut a dhol a-steach don eòlaire (thèid [an .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) a chuir gu bàs gu fèin-ghluasadach às deidh dhut a dhol a-steach don eòlaire).

Is e an ciall: eadar-theangachadh Sìneach gu Seapanais, Coirèanais, Beurla, eadar-theangachadh Beurla gu gach cànan eile. Ma tha thu dìreach airson taic a thoirt do Shìonais is Beurla, faodaidh tu dìreach sgrìobhadh `zh: en` .

Is e an ciall: eadar-theangachadh Sìneach gu Seapanais, Coirèanais, Beurla, eadar-theangachadh Beurla gu gach cànan eile. Ma tha thu dìreach airson taic a thoirt do Shìonais is Beurla, faodaidh tu dìreach sgrìobhadh `zh: en` .

* [còd aghaidh](https://github.com/xxai-art/web)
* [Pacaidean cànain airson na làraich gu h-iomlan](https://github.com/xxai-art/web/tree/main/i18n)
* [Pacaidean cànain airson modalan logadh a-steach](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Sgrìobhainnean ioma-chànanach làrach-lìn](https://github.com/xxai-doc)

Is e an cànan prògramadh aghaidh aghaidh [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , a chuireas ri cuid de fheartan stèidhichte air co-chòrdadh coffeescript, faic [./coffee_plus.md](./coffee_plus.md) .

## Eadar-nàiseantachd làraich-lìn agus sgrìobhainnean

Tog air na 3 pròiseactan a leanas

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Is e an iar-leasachan `.mdt` , faodaidh tu an co-chòrdadh coltach ri `<+ ./coffee_plus/import.js>` a chleachdadh gus iomradh a thoirt air faidhlichean taobh a-muigh, agus comharradh sìos leis an iar-leasachan `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Cha dèan eadar-theangachadh Markdown còdan is ceanglaichean eadar-theangachadh, agus cuiridh e seantansan eadar-theangaichte air dòigh. Ma thèid an t-eadar-theangachadh atharrachadh ach nach eil an teacsa tùsail air atharrachadh, cha dèan e a-rithist sgrìobhadh thairis air atharrachadh an eadar-theangachaidh.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Faidhlichean cànain airson làraichean-lìn gineadh `yaml` eadar-theangachadh.

### Stiùireadh fèin-ghluasad eadar-theangachadh sgrìobhainnean

Faic stòr còd [xxai-art/doc](https://github.com/xxai-art/doc)

Thathas a’ moladh nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) a stàladh an toiseach, agus an uairsin `direnv allow` às deidh dhut a dhol a-steach don eòlaire (thèid [an .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) a chuir gu bàs gu fèin-ghluasadach às deidh dhut a dhol a-steach don eòlaire).

Gus am bunait còd mòr eadar-theangachadh gu ceudan de chànanan a sheachnadh, chruthaich mi bunait còd air leth airson gach cànan agus chruthaich mi buidheann airson bunait còd a stòradh

Le bhith a’ suidheachadh caochladair na h-àrainneachd `GITHUB_ACCESS_TOKEN` agus an uairsin a’ ruith [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) cruthaichidh tu stòr a’ chòd gu fèin-obrachail.

Gu dearbh, faodaidh tu cuideachd a chuir ann am bunait còd.

Iomradh sgriobt eadar-theangachadh [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Tha an còd sgriobt air a mhìneachadh mar a leanas:

Tha [bunx](https://bun.sh/docs/cli/bunx) na àite npx, a tha nas luaithe. Gu dearbh, mura h-eil bun agad air a chuir a-steach, faodaidh tu `npx` a chleachdadh na àite.

`bunx mdt zh` a' toirt seachad `.mdt` san eòlaire zh mar `.md` , faic an dà fhaidhle ceangailte gu h-ìosal

* [cofaidh_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [cofaidh_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

Is e `bunx i18n` am prìomh chòd airson eadar-theangachadh (mura h-eil agad ach `nodejs` a chuir a-steach, ach nach eil `bun` agus `direnv` air an stàladh, faodaidh tu cuideachd `npx i18n` a ruith airson eadar-theangachadh).

Parsaidh e [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) , tha rèiteachadh `i18n.yml` san sgrìobhainn seo mar a leanas:

```
en:
zh: ja ko en
```

Is e an ciall: eadar-theangachadh Sìneach gu Seapanais, Coirèanais, Beurla, eadar-theangachadh Beurla gu gach cànan eile. Ma tha thu dìreach airson taic a thoirt do Shìonais is Beurla, faodaidh tu dìreach sgrìobhadh `zh: en` .

Is e am fear mu dheireadh [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , a bhios a’ toirt a-mach an t-susbaint eadar am prìomh thiotal agus a’ chiad fho-thiotal de `README.md` gach cànan gus inntrigeadh `README.md` a ghineadh. Tha an còd gu math sìmplidh, faodaidh tu coimhead air thu fhèin.

Tha Google API air a chleachdadh airson eadar-theangachadh an-asgaidh. Mura h-urrainn dhut faighinn gu Google, feuch an cuir thu air dòigh agus suidhich neach-ionaid, mar:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Ginidh an sgriobt eadar-theangachaidh tasgadan eadar-theangachaidh ann an eòlaire `.i18n` , feuch an cuir thu sùil air le `git status` agus cuir ris an stòr chòd gus eadar-theangachadh a sheachnadh.

Feuch an ruith thu `bunx i18n` a h-uile uair a dh’ atharraicheas tu an t-eadar-theangachadh gus an tasgadan ùrachadh.

Ma thèid an teacsa tùsail agus an eadar-theangachadh atharrachadh aig an aon àm, bidh an tasgadan troimh-a-chèile, mar sin ma tha thu airson atharrachadh, chan urrainn dhut ach aon atharrachadh, agus an uairsin ruith `bunx i18n` gus an tasgadan ùrachadh.
