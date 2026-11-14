<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd2lzob3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-rating" /></template>
<style>
.yd2lzob3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h3l3 1.5l-3 1.5h-3v-3m0 5.25h7l3 1.5l-3 1.5h-7v-3m0 5.25h11l3 1.5l-3 1.5h-11v-3m0 5.25h15l3 1.5l-3 1.5h-15v-3");
}

</style>
