<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygcatlbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-cover" /></template>
<style>
.ygcatlbmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 14h11L16 21H8Zm5.5 0V8m0 2c0-3-2.5-5-5.5-5c0 3 2.5 5 5.5 5Zm0-2c0-2.5 2-4.5 5-4.5C17 6 15 8 12 8Z");
}

</style>
