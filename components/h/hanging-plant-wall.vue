<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro46y3bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hanging-plant-wall" /></template>
<style>
.ro46y3bgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5V10m0-6h11M3 8.5L7.5 4M14 4v10m-3.3 0h6.6a1.75 1.75 0 0 1 1.705 2.144l-.692 3a1.75 1.75 0 0 1-1.705 1.356h-5.216a1.75 1.75 0 0 1-1.705-1.356l-.692-3A1.75 1.75 0 0 1 10.7 14m.05 0c-2.75-1-3.5-3.25-3-5c2.5.5 3.5 2.5 3 5m6.5 0c2.75-1 3.5-3.25 3-5c-2.5.5-3.5 2.5-3 5");
}

</style>
