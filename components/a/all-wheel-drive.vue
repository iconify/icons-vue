<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6347rbnh"/><path class="rg-09nc8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:all-wheel-drive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rg-09nc8x {
  d: path("M8.5 8.5q3.5-2 7 0m-7 7.5q3.5 1.5 7 0");
}

.t6347rbnh {
  d: path("M12 2.5zA3.5 3.5 0 0 1 15.5 6v12a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 8.5 18V6A3.5 3.5 0 0 1 12 2.5M4.5 10V4.5M3 6l1.5-1.5L6 6m13.5 4V4.5M18 6l1.5-1.5L21 6M4.5 19.5V14M3 15.5L4.5 14L6 15.5m13.5 4V14M18 15.5l1.5-1.5l1.5 1.5");
}

</style>
