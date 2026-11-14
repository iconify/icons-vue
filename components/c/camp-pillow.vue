<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1g12e33u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camp-pillow" /></template>
<style>
.k1g12e33u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5q7.5-2.5 15 0q1.5 5.5 0 11q-7.5 2.5-15 0q-1.5-5.5 0-11Zm15 0l2-2m-1.25-1.25l2.5 2.5");
}

</style>
