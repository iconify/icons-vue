<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8rdc0baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earth-moon-sun" /></template>
<style>
.e8rdc0baq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm10.5-7a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM19 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
