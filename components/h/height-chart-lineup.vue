<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czhrrsj0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:height-chart-lineup" /></template>
<style>
.czhrrsj0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 8.75h2c1.25 0 2.25.25 2.5 1.5l2 2.5c.25 1-.25 1.5-1.25 1.5c-.75 0-1-.25-1.25-.75L12 12l.5 2l.75 4.25c.25.75-.25 1.25-1 1.25h-1c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75Zm-2-4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M18.5 3v18m0-18h3m-3 6h3m-3 6h3m-3 6h3");
}

</style>
