<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikddgqr_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:filter-sliders" /></template>
<style>
.ikddgqr_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6h9m-6 6H9m.5 6h5m-1-12a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5 0h2.5m0-6h3");
}

</style>
