<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qt4afwy9g"/><circle class="wertabc3z"/><circle class="q7xtx_x3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:divide-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7xtx_x3w {
  cx: 12px;
  cy: 17.5px;
  r: 1.5px;
}

.qt4afwy9g {
  d: path("M6.5 12h11");
}

.wertabc3z {
  cx: 12px;
  cy: 6.5px;
  r: 1.5px;
}

</style>
