<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oyi48ib5d"/><rect class="awdp_9zbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heavy-stapler" /></template>
<style>
.awdp_9zbi {
  width: 18px;
  height: 4px;
  x: 3px;
  y: 15px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oyi48ib5d {
  d: path("m4.24 8.31l13.52-2.12Q19 6 20 6.75t1 2v1.5q0 1.25-1.25 1.25H4.25Q3 11.5 3 10.25v-.5Q3 8.5 4.24 8.31M19.5 11.5V15");
}

</style>
