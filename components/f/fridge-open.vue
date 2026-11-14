<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="td7a7siqn"/><path class="syr07nbjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fridge-open" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.syr07nbjz {
  d: path("m15.731 3.137l3.5 1A1.75 1.75 0 0 1 20.5 5.82v12.36a1.75 1.75 0 0 1-1.269 1.683l-3.5 1A1.75 1.75 0 0 1 13.5 19.18V4.82a1.75 1.75 0 0 1 2.231-1.683M3 9h10.5M3 15h10.5");
}

.td7a7siqn {
  d: path("M6.5 2.5H10A3.5 3.5 0 0 1 13.5 6v12a3.5 3.5 0 0 1-3.5 3.5H6.5A3.5 3.5 0 0 1 3 18V6a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
