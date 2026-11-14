<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4a169baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frost-alert" /></template>
<style>
.e4a169baw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5v16m-7-12l12.069 6.896M3.5 14.5l14-8M8.25 3.25L10.5 5.5l2.25-2.25m-4.5 14.5l2.25-2.25l2.25 2.25m3-12.75l-1 3l3.25.75m-15 0L6.25 8l-1-3M3 12.25l3.25.75l-1 3M18 14.75v3.5M18 21h.01");
}

</style>
