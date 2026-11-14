<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tumdpdbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bed-double" /></template>
<style>
.tumdpdbyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4v16m0-8.5h16a2 2 0 0 1 2 2v3H3m18 0V20M5.75 7.5H10v4H5.75Zm7 0H17v4h-4.25Z");
}

</style>
