<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkrcfhgkm"/><path class="m33ss0bea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:debug-restart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m33ss0bea {
  d: path("M18 2.5V6h-3.5");
}

.tkrcfhgkm {
  d: path("M20.5 12A8.5 8.5 0 1 1 18 6");
}

</style>
