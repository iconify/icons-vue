<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmqbo1pue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cardiac-rehab" /></template>
<style>
.kmqbo1pue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.215 17.657C13.466 19.104 12 20 12 20s-1.444-.883-3.176-2.31M3.709 6.231A4.72 4.72 0 0 1 7.75 4C9.5 4 11.1 5 12 6.5C12.9 5 14.5 4 16.25 4a4.72 4.72 0 0 1 4.015 2.189M6.5 12h11M3 9h3v6H3Zm15 0h3v6h-3Z");
}

</style>
