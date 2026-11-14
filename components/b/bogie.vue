<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys8rxacpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bogie" /></template>
<style>
.ys8rxacpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19v3.25h-19Zm9.5 0v-3M3.5 16a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm10 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM7 16h.01M17 16h.01");
}

</style>
