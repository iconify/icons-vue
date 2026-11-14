<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dd2yl2afd"/><path class="kou6_ccjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:judo-ippon-sign" /></template>
<style>
.dd2yl2afd {
  d: path("M8.5 2.5h7A3.5 3.5 0 0 1 19 6v7a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 13V6a3.5 3.5 0 0 1 3.5-3.5m3.5 14v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kou6_ccjr {
  fill: currentColor;
  d: path("M8.5 9.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
