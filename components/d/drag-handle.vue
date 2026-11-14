<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbd7qgbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drag-handle" /></template>
<style>
.zbd7qgbcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 5.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm6 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM8 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm6 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm-6 6.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm6 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
