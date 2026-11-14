<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wnj1qjbvj"/><path class="bmh31vbwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:e-bike" /></template>
<style>
.bmh31vbwi {
  d: path("M6 16.5L9 11h6.5l2.5 5.5m-5.25-14L10 5.5h4l-2.75 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnj1qjbvj {
  d: path("M2.25 16.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m12 0a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
