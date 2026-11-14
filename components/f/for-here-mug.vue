<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smtigjq2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:for-here-mug" /></template>
<style>
.smtigjq2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4h10v9q0 4-4 4h-2q-4 0-4-4Zm10 3h1a2.5 2.5 0 0 1 0 5h-1m-14 5h19Q20 20.5 12 20.5T2.5 17");
}

</style>
