<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2hydsvot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coolant-nozzle" /></template>
<style>
.v2hydsvot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h7A3.5 3.5 0 0 1 13 6v2.5L12 10h-2L9 8.5V7a.5.5 0 0 0-.5-.5h-6m2.875 12.25h13.25A1.375 1.375 0 0 1 20 20.125a1.375 1.375 0 0 1-1.375 1.375H5.375A1.375 1.375 0 0 1 4 20.125a1.375 1.375 0 0 1 1.375-1.375m5.625-6l1.25 2a1.25 1.25 0 1 1-2.5 0Z");
}

</style>
