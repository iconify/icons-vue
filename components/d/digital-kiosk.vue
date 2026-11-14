<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfr1zeb6q"/><path class="myqgb8bso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-kiosk" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.myqgb8bso {
  d: path("M11.5 5.25h1A1.75 1.75 0 0 1 14.25 7v3a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 9.75 10V7a1.75 1.75 0 0 1 1.75-1.75M10 15.5h4");
}

.xfr1zeb6q {
  d: path("M7 21.5v-17a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v17m-12.5 0h15");
}

</style>
