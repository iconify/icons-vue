<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bei5ppbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:folder-dashed" /></template>
<style>
.bei5ppbai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10V7a2 2 0 0 1 2-2h1.5m3 0l2 2h1m3 0H19a2 2 0 0 1 2 2v1.5m0 3.5v3a2 2 0 0 1-2 2h-2m-6.5 0h3M7 19H5a2 2 0 0 1-2-2v-3");
}

</style>
