<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m85oqyb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ipd-adjust" /></template>
<style>
.m85oqyb4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.75c2-4 6-4 8 0c-2 4-6 4-8 0Zm11 0c2-4 6-4 8 0c-2 4-6 4-8 0Zm-7 0h.01m10.99 0h.01M5 16.5h14M7.5 14L5 16.5L7.5 19m9-5l2.5 2.5l-2.5 2.5");
}

</style>
