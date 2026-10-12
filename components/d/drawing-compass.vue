<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="h1nvq6bbq"/><path class="k4doyybfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drawing-compass" /></template>
<style>
.h1nvq6bbq {
  cx: 12px;
  cy: 5.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4doyybfm {
  d: path("M10.75 7.75L5.75 21m7.5-13.25l5 13.25m-11.5-5.5c3.25 1.75 7.25 1.75 10.5 0");
}

</style>
