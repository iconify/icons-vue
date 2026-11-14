<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zary94bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-medical-supplies" /></template>
<style>
.zary94bvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 8h7.5A5.25 5.25 0 0 1 21 13.25v1.5A5.25 5.25 0 0 1 15.75 20h-7.5A5.25 5.25 0 0 1 3 14.75v-1.5A5.25 5.25 0 0 1 8.25 8M9 8V6a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2m-3 3.5v5M9.5 14h5");
}

</style>
