<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bft5sxx2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:groomed-slope" /></template>
<style>
.bft5sxx2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5C5 8 8.5 4.5 12 4.5s7 3.5 9.5 15M13 9l3 6.5m-6.5-5l3 6.5M7 15l1.5 3.5");
}

</style>
