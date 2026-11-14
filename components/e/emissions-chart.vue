<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io93xpbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emissions-chart" /></template>
<style>
.io93xpbga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v17.5h9.1M6.5 5v12.5M9.75 9v8.5M13 13v4.5m2.5 4c0-4.5 2-6 6-6q0 6-6 6Zm0 0l3-3");
}

</style>
