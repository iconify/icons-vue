<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGgp555bPJ" x1="45.082%" x2="55.522%" y1="-1.343%" y2="97.61%"><stop offset="0%" class="bzg--8baj"/><stop offset="32%" class="w_tftibgk"/><stop offset="79%" class="dhi0k247e"/><stop offset="100%" class="xtrtznbzt"/></linearGradient><linearGradient id="SVGBKBSTcCW" x1="-2.942%" x2="100.445%" y1="38.992%" y2="62.105%"><stop offset="0%" class="k_ry59jvu"/><stop offset="100%" class="r_lf9ybqi"/></linearGradient><linearGradient id="SVGpCKRwebu" x1="-3.308%" x2="111.745%" y1="71.807%" y2="15.462%"><stop offset="0%" class="rwcjds48k"/><stop offset="18%" class="jgajcibaw"/><stop offset="49%" class="y3n2d5b8h"/><stop offset="89%" class="xe5oe8bcp"/><stop offset="100%" class="i2k1k6a9b"/></linearGradient></defs><path fill="url(#SVGgp555bPJ)" class="ndf0_w3jq"/><path fill="url(#SVGBKBSTcCW)" class="urrbgccau"/><path fill="url(#SVGpCKRwebu)" class="n6kv9w4yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:jetbrains-space-icon" /></template>
<style>
.bzg--8baj {
  stop-color: var(--svg-color--fcf84a, #fcf84a);
}

.dhi0k247e {
  stop-color: var(--svg-color--36cdd2, #36cdd2);
}

.i2k1k6a9b {
  stop-color: var(--svg-color--293896, #293896);
}

.jgajcibaw {
  stop-color: var(--svg-color--0490dd, #0490dd);
}

.k_ry59jvu {
  stop-color: var(--svg-color--3bea62, #3bea62);
}

.n6kv9w4yd {
  d: path("M158.894 109.223C147.187 186.6 46.258 255.99 46.258 255.99c91.781-8.67 172.23-63.622 209.742-146.768z");
}

.ndf0_w3jq {
  d: path("M46.36 255.991c91.075-7.978 170.982-63.92 209.64-146.768C208.12 40.799 129.873.033 46.36 0Q35.2 0 23.936.99c-38.612 82.903-30.064 180.109 22.424 255");
}

.r_lf9ybqi {
  stop-color: var(--svg-color--087cfa, #087cfa);
}

.rwcjds48k {
  stop-color: var(--svg-color--009ae5, #009ae5);
}

.urrbgccau {
  d: path("M24.209 1.024a301.4 301.4 0 0 1 134.685 108.199H256C208.263 40.76 130.062-.03 46.6 0Q35.437 0 24.208 1.024");
}

.w_tftibgk {
  stop-color: var(--svg-color--abe682, #abe682);
}

.xe5oe8bcp {
  stop-color: var(--svg-color--2346a1, #2346a1);
}

.xtrtznbzt {
  stop-color: var(--svg-color--07c3f2, #07c3f2);
}

.y3n2d5b8h {
  stop-color: var(--svg-color--1073c6, #1073c6);
}

</style>
