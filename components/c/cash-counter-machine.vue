<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="za6zh9b7y"/><path class="fre7ogb0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cash-counter-machine" /></template>
<style>
.fre7ogb0g {
  d: path("M7 14.25h6a1.5 1.5 0 0 1 1.5 1.5v1.5a1.5 1.5 0 0 1-1.5 1.5H7a1.5 1.5 0 0 1-1.5-1.5v-1.5a1.5 1.5 0 0 1 1.5-1.5m1.5 0v4.5m3-4.5v4.5M18 16.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.za6zh9b7y {
  d: path("M6 11.5h12a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-3A3.5 3.5 0 0 1 6 11.5m3 0V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v7.5m-7.25 0L4.5 5.75L9 3.25m7.25 8.25l3.25-5.75l-4.5-2.5");
}

</style>
