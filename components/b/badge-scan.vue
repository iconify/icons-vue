<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5yg_gbws"/><path class="e2atxtbbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badge-scan" /></template>
<style>
.e2atxtbbp {
  d: path("M10.25 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M8.5 18.75c0-2 1.5-3.5 3.5-3.5s3.5 1.5 3.5 3.5m-13 0h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5yg_gbws {
  d: path("M8 6h8a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V9.5A3.5 3.5 0 0 1 8 6m2 0V2.5M14 6V2.5");
}

</style>
