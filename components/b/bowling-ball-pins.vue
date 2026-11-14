<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjb9_kb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bowling-ball-pins" /></template>
<style>
.mjb9_kb7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 16.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM12.25 12h2.5c1.25-2 1-4.25-.5-6c.75-.75.75-1.5.75-2a1.5 1.5 0 0 0-3 0c0 .5 0 1.25.75 2c-1.5 1.75-1.75 4-.5 6Zm6.25 4H21c1.25-2 1-4.25-.5-6c.75-.75.75-1.5.75-2a1.5 1.5 0 0 0-3 0c0 .5 0 1.25.75 2c-1.5 1.75-1.75 4-.5 6Z");
}

</style>
