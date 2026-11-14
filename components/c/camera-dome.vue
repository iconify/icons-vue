<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekl8yd8yb"/><path class="trj1-nbrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-dome" /></template>
<style>
.ekl8yd8yb {
  d: path("M5 5.5h14M3.5 9h17a8.5 8.5 0 0 1-17 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.trj1-nbrn {
  d: path("M10.5 13.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
