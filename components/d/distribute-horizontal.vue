<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uoxilcjhg"/><rect class="xrg7h-bjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:distribute-horizontal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uoxilcjhg {
  d: path("M3.75 2.75v18.5m16.5-18.5v18.5");
}

.xrg7h-bjv {
  width: 6px;
  height: 12.5px;
  x: 9px;
  y: 5.75px;
  rx: 1.5px;
}

</style>
