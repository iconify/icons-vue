<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dilea4bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:candle-hazard" /></template>
<style>
.dilea4bxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11.5h8v10H4Zm4-9c1.75 1.75 2.5 2.75 2.5 4a2.5 2.5 0 0 1-5 0c0-1.25.75-2.25 2.5-4ZM8 9v2.5m10 3V18m0 3h.01");
}

</style>
