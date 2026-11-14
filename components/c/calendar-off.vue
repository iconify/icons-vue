<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g99tynsik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-off" /></template>
<style>
.g99tynsik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.9 5h11.6v11.6m-3.9 3.9H3.5V7.4M8 3v1.1M16 3v4M3.5 10h2.6m7.8 0h6.6m-17-6.5l17 17");
}

</style>
