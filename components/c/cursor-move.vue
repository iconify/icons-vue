<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9e1v7but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cursor-move" /></template>
<style>
.u9e1v7but {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12h12m-6-6v12m-9.5-6L6 9v6Zm19 0L18 9v6ZM12 2.5L9 6h6Zm0 19L9 18h6Z");
}

</style>
