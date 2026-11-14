<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8dsa0cem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blast-zone" /></template>
<style>
.b8dsa0cem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.65 2.644a9.5 9.5 0 0 1 5.627 3.25m1.65 2.857a9.5 9.5 0 0 1 0 6.498m-1.65 2.857a9.5 9.5 0 0 1-5.627 3.25m-3.3 0a9.5 9.5 0 0 1-5.627-3.25m-1.65-2.857a9.5 9.5 0 0 1 0-6.498m1.65-2.857a9.5 9.5 0 0 1 5.627-3.25M17 12l-2.75 1l1.25 2.5l-2.5-1.25L12 17l-1-2.75l-2.5 1.25L9.75 13L7 12l2.75-1L8.5 8.5L11 9.75L12 7l1 2.75l2.5-1.25l-1.25 2.5Z");
}

</style>
