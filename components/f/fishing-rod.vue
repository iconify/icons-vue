<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="htweieb1l"/><circle class="po2i4dbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fishing-rod" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htweieb1l {
  d: path("m3.5 20.75l3.26-3.67m2.64-3L18.75 3.5m0 0v13a2.25 2.25 0 0 1-4.5 0v-.75");
}

.po2i4dbso {
  cx: 8.08px;
  cy: 15.58px;
  r: 2px;
}

</style>
