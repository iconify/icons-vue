<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk7wrybcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:haptics-off" /></template>
<style>
.bk7wrybcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.4 4.5H16v7.6m-.4 7.4H8v-7.6m-3.25 3.481a8 8 0 0 1 0-6.762m14.5 0a8 8 0 0 1 0 6.762M3.5 3.5l17 17");
}

</style>
