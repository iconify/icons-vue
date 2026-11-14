<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l548te9ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dish-towel" /></template>
<style>
.l548te9ys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 6V4.5a1.75 1.75 0 0 1 3.5 0V6M5 6h14v13q-1.75 2.5-3.5 0T12 19t-3.5 0T5 19Zm0 4h14");
}

</style>
