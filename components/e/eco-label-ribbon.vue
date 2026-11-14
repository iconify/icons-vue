<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fyrlk0i8z"/><path class="x0wm1p3jg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eco-label-ribbon" /></template>
<style>
.fyrlk0i8z {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x0wm1p3jg {
  d: path("m9.5 15l-1 6.5l3.5-2l3.5 2l-1-6.5m-5-3.5c0-3 2-5 5-5c0 3-2 5-5 5");
}

</style>
