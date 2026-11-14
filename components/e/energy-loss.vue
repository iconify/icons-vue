<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl1v0bc5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-loss" /></template>
<style>
.hl1v0bc5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 11h6v8H9Zm-6.5 4h3.75m-2-2l2 2l-2 2m13.5-2h3.75m-1.75-1.5L21.5 15l-1.75 1.5M10.25 8c-1.25-1.25 1.25-2.75 0-4.5m4 4.5c-1.25-1.25 1.25-2.75 0-4.5");
}

</style>
