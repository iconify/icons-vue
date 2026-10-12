<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn5q8s7bc"/><path class="g12pkbboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chevron-up-square" /></template>
<style>
.bn5q8s7bc {
  d: path("M5.25 18.5L12 11.75l6.75 6.75");
}

.g12pkbboi {
  d: path("M5.25 12.25L12 5.5l6.75 6.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
