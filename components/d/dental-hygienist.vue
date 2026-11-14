<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-4pai6nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-hygienist" /></template>
<style>
.p-4pai6nz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.572 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.931 0 1.814.108 2.625.311M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm12 8.25c-.75-1-3-1-3 1.25c0 1.5.5 2.25.75 3.25L17 21.5h.75l.75-1.75l.75 1.75H20l.75-1.75c.25-1 .75-1.75.75-3.25c0-2.25-2.25-2.25-3-1.25Z");
}

</style>
