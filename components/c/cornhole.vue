<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c2r0s2ffc"/><path class="gy9-h1dhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cornhole" /></template>
<style>
.c2r0s2ffc {
  d: path("M8.386 3h7.228a1.75 1.75 0 0 1 1.703 1.349l3.177 13.5A1.75 1.75 0 0 1 18.79 20H5.21a1.75 1.75 0 0 1-1.704-2.151l3.177-13.5A1.75 1.75 0 0 1 8.386 3");
}

.gy9-h1dhu {
  d: path("M9.75 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m1.75 6h1a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 12.5 17h-1a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
