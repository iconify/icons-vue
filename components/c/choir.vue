<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahzq61h6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:choir" /></template>
<style>
.ahzq61h6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2 21.5c0-3 5.25-3.5 6.5-1.25c1.25-2.25 5.75-2.25 7 0C16.75 18 22 18.5 22 21.5M13.5 8V3l2.75 1.5M10 8a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 10 8Z");
}

</style>
