<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwrtcgk9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-multitool" /></template>
<style>
.qwrtcgk9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12h4a1 1 0 0 1 1 1v7.5a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V13a1 1 0 0 1 1-1ZM5.5 3A2.5 2.5 0 1 1 3 5.5m4.25 1.75L12 12m0 0V3.5h2.25M12 12l6.5-6.5M17 4l3 3m-8 8h.01");
}

</style>
