<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo4wqcbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garment-steamer" /></template>
<style>
.bo4wqcbtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 10h8A1.75 1.75 0 0 1 15 11.75a1.75 1.75 0 0 1-1.75 1.75h-8a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 5.25 10m8.5 3.5h.401a1.5 1.5 0 0 1 1.286.728l2.617 4.363a1.42 1.42 0 0 1-.429 1.909a1.21 1.21 0 0 1-1.745-.451l-2.807-5.438a.762.762 0 0 1 .677-1.111M6.5 11.75h.01m2.74 0h.01m2.74 0h.01M18.75 20c1.75-.5 2.75-2.5 2.5-5M6 8.5c-1-1.5 1-3 0-5m3.25 5c-1-1.5 1-3 0-5m3.25 5c-1-1.5 1-3 0-5");
}

</style>
