<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vw18n55xz"/><path class="aly6ip2cj"/><path class="zkjcegn9b"/><path class="c80skftax"/><path class="eud-3ptuk"/><path class="tk71h5gnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:locked-list-duotone-bold" /></template>
<style>
.aly6ip2cj {
  d: path("M2 13a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.c80skftax {
  d: path("M15 8h7");
}

.eud-3ptuk {
  d: path("M15 12h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tk71h5gnp {
  d: path("M15 16h7");
}

.vw18n55xz {
  fill: currentColor;
  d: path("M2 13a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zkjcegn9b {
  d: path("M4 11a3 3 0 0 1 6 0");
}

</style>
