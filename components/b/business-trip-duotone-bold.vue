<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qh3x50ajr"/><path class="bmzq19b2x"/><path class="a-v3knb-a"/><path class="qbq59yb6c"/><path class="bac4tq45c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:business-trip-duotone-bold" /></template>
<style>
.a-v3knb-a {
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.bac4tq45c {
  d: path("m11 2 2.5 2.5H19L16.5 7H11Z");
}

.bmzq19b2x {
  fill: currentColor;
  d: path("m11 2 2.5 2.5H19L16.5 7H11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qbq59yb6c {
  d: path("M9 12V9.5h6V12");
}

.qh3x50ajr {
  fill: currentColor;
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
