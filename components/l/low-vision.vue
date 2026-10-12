<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0y37cc9t"/><circle class="gp0egaclj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:low-vision" /></template>
<style>
.f0y37cc9t {
  d: path("M2.75 12c1.9-4.1 5.3-6.75 9.25-6.75S19.35 7.9 21.25 12m-17.5 2.25L5.25 16M8 17.75l2 .75m4 0l2-.75M18.75 16l1.5-1.75");
}

.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
