<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6npeabzr"/><path class="lwvebc47i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-hatchery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwvebc47i {
  d: path("M11.5 13c1.5-3 4.25-3 5.25 0l1.5-1.75v3.5L16.75 13c-1 3-3.75 3-5.25 0");
}

.p6npeabzr {
  d: path("M3 3.5V18a2.5 2.5 0 0 0 2.5 2.5h13A2.5 2.5 0 0 0 21 18V3.5m-12.25 17V8");
}

</style>
