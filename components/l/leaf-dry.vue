<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veapk8boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-dry" /></template>
<style>
.veapk8boz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 19l-.5-5l2-1.5V9l3-1l1-3H14l2-1.5l3.5 1l1 3.5l-1.5 2v3.5l-3 1l-1 3l-3.5.25L10 19.5Zm-1.5 1.5L13 11");
}

</style>
