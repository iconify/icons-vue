<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fsuht_b8c"/><path class="i8o-lgigj"/><path class="xoaby-lkq"/><path class="tntcgmbin"/><path class="mlg1u0arq"/><path class="acyg6nb1v"/><path class="ctdwryy5l"/><path class="d5_p0tpur"/><path class="ciwbnxb_b"/><path class="jnysnpbhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fork-duotone-bold" /></template>
<style>
.acyg6nb1v {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ciwbnxb_b {
  d: path("M3 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ctdwryy5l {
  d: path("M10.5 9.5 6 14");
}

.d5_p0tpur {
  d: path("M13.5 9.5 18 14");
}

.fsuht_b8c {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i8o-lgigj {
  fill: currentColor;
  d: path("M3 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jnysnpbhj {
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mlg1u0arq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 9.5 18 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tntcgmbin {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 9.5 6 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xoaby-lkq {
  fill: currentColor;
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
