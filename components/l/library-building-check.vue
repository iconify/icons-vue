<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik5nspohx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:library-building-check" /></template>
<style>
.ik5nspohx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5L12 3l9 5.5ZM3 21h10.8m5.9 0H21M6.5 11.5V18m5-6.5v5.8m3.25.7l2 2L21 15.75");
}

</style>
