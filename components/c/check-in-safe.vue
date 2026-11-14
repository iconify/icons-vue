<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygkjoublm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:check-in-safe" /></template>
<style>
.ygkjoublm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3.5 21c0-3.75 3.25-6.25 7.5-6.25q1.503 0 2.671.334M14.75 18l2 2L21 15.75");
}

</style>
