<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="oxeexobnw"/><path class="kqdq7bcxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crane" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqdq7bcxw {
  d: path("M2.75 6.75h18.5m-17.5 0l4.13-4l6.12 4m-4.25 3L6 13.5l3.75 3.75m7.75-10.5v8.75a1.75 1.75 0 0 1-3.5 0");
}

.oxeexobnw {
  width: 3.75px;
  height: 14.5px;
  x: 6px;
  y: 6.75px;
  rx: 1px;
}

</style>
