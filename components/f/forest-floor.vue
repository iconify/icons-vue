<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snsh3ubwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forest-floor" /></template>
<style>
.snsh3ubwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11a6 6 0 0 1 12 0Zm4 0v9m4-9v9m3 0q1-6 7.5-7q-.5 4-7.5 7ZM2.5 20h19");
}

</style>
