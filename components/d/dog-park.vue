<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rdzfmkniu"/><path class="tsv43ybdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-park" /></template>
<style>
.rdzfmkniu {
  d: path("M7.5 19.5c-2 0-2.5-2.5-1.25-4.5l5.25-6V6.5c0-1.75 1.25-3 3-3c1.5 0 2.5 1 2.75 2l1.75.75c.75.25.75 1.5 0 2c-.5.5-1.25.75-2.5 1V19.5Zm-5 2h19");
}

.tsv43ybdd {
  d: path("M13.25 4c-1.25.5-1.5 3-.5 4.75c1-.75 1.25-3.25.5-4.75Zm2.25 1.75h.01M9 19.5c0-2.75 1.75-4.5 4.25-4.5M6 16.5c-2.25-.25-3.25-1.75-3-3.75m16 8.75l-.5-2m2.25 2l.5-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
