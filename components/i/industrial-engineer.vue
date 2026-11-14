<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9bbixbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:industrial-engineer" /></template>
<style>
.i9bbixbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8a4 4 0 0 1 8 0m-10 0h12m-10 0v1.5a4 4 0 0 0 8 0V8M3 21c0-2.75 2.75-4.5 6.5-4.5S16 18.25 16 21m2.75-13.5h3V21h-3Z");
}

</style>
