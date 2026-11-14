<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrgk909jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:key-x" /></template>
<style>
.vrgk909jy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm7-3L20 4m-3 3l2.5 2.5m-5 0l2 2m-1 4l5 5m0-5l-5 5");
}

</style>
