<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qqm3sm-he"/><path class="ddr0zpdgr"/><path class="zugrvnb7t"/><path class="yfx_djbhn"/><path class="cpo3zsjsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drought-duotone-bold" /></template>
<style>
.cpo3zsjsl {
  d: path("m16 13 -4 4 4 4");
}

.ddr0zpdgr {
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.qqm3sm-he {
  fill: currentColor;
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
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

.yfx_djbhn {
  d: path("m6 13 4 4 -4 4");
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
