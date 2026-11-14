<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwhyhbbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fitting-room-limit" /></template>
<style>
.fwhyhbbnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5v-1a2 2 0 1 0-2-2m3.436 9H2.5l9.5-6l6.341 4.005M15.5 15.75c.25-1 1.25-1.5 2.5-1.5c1.5 0 2.5.75 2.5 2c0 1-1 1.5-2.25 1.5c1.5 0 2.5.75 2.5 2s-1.25 2-2.75 2c-1.25 0-2.25-.5-2.75-1.5");
}

</style>
