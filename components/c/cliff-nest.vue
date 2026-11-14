<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yozp8sbjk"/><path class="l_elbgbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cliff-nest" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_elbgbib {
  d: path("M7.25 7a1.75 3 0 1 0 3.5 0a1.75 3 0 1 0-3.5 0m6 0a1.75 3 0 1 0 3.5 0a1.75 3 0 1 0-3.5 0");
}

.yozp8sbjk {
  d: path("M2.5 16h19l-2 4.5H5l-1.5-2Zm2-6h15c0 3.5-3 6-7.5 6s-7.5-2.5-7.5-6");
}

</style>
