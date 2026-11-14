<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux5refe6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:document-retention" /></template>
<style>
.ux5refe6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10V4a1 1 0 0 1 1-1h9a1 1 0 0 1 1 1v6M3 10h18v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm6.5-3.5h5m-4.5 8h4");
}

</style>
