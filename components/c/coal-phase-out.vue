<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs1k8db7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coal-phase-out" /></template>
<style>
.xs1k8db7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.541 19.459l-.041.041h-8l-3.5-7l1.521-3.041m3.61-4.335L14 4l5.5 3.5l1 7l-.999.999M3.5 3.5l17 17");
}

</style>
