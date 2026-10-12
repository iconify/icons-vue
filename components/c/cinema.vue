<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="his22sbrb"/><path class="gtmwntbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cinema" /></template>
<style>
.gtmwntbok {
  d: path("m10.75 6.75l3.5 1.75l-3.5 1.75ZM4 17.5q8-2.5 16 0m-17 3q9-2.5 18 0");
}

.his22sbrb {
  width: 18px;
  height: 9px;
  x: 3px;
  y: 4px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
