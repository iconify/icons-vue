<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ns5x_unjo"/><path class="fv2zf2h1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-teller-window" /></template>
<style>
.fv2zf2h1z {
  d: path("M9.75 7a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-1.5 8c0-2 1.5-3.5 2.75-3.75M15.75 15c0-2-1.5-3.5-2.75-3.75M10 15a2 2 0 0 1 4 0");
}

.ns5x_unjo {
  d: path("M5 2.5h14V15H5Zm-2.5 15h19v3h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
