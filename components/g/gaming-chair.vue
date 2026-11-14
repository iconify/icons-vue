<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oay6uvbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gaming-chair" /></template>
<style>
.oay6uvbok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 13V5a2.5 2.5 0 0 1 2.5-2.5h3A2.5 2.5 0 0 1 16 5v8M5 13h14v3.5H5Zm5.5-6.5h3m-1.5 10V19m-5.5 2.5L12 19l5.5 2.5");
}

</style>
