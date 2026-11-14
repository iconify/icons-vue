<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v54463bfp"/><path class="h-wohubfl"/><path class="oz2_yebcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-route-sign" /></template>
<style>
.h-wohubfl {
  d: path("M7 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oz2_yebcj {
  d: path("M9 11.5L11 8h3.5l-2.25 3.5ZM14.5 8l.5 3.5M14.5 8L14 6");
}

.v54463bfp {
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v7a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 13V6a3.5 3.5 0 0 1 3.5-3.5m4.5 14v5");
}

</style>
