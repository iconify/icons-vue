<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="notanabip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-tower-monopole" /></template>
<style>
.notanabip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 21.5h9m-6.25 0L12 9l1.75 12.5m-3.25-19h3V9h-3Zm-5.75 1h3v5h-3Zm11.5 0h3v5h-3Z");
}

</style>
