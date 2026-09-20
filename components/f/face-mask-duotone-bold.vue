<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tu3bv3eig"/><path class="ml2x0ac7x"/><path class="yoftwf7ei"/><path class="gqwusxz8h"/><path class="mbifgmx_w"/><path class="tp86gnbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:face-mask-duotone-bold" /></template>
<style>
.gqwusxz8h {
  d: path("M3 12h18v3a12 12 0 0 1 -18 0Z");
}

.mbifgmx_w {
  d: path("M3 12V8");
}

.ml2x0ac7x {
  fill: currentColor;
  d: path("M3 12h18v3a12 12 0 0 1 -18 0Z");
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

.tp86gnbwd {
  d: path("M21 12V8");
}

.tu3bv3eig {
  fill: currentColor;
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yoftwf7ei {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
