<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j19i-pxvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:block-x" /></template>
<style>
.j19i-pxvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.41 4.458L12 2.5L20.25 7v9.303m-4.655 3.236L12 21.5L3.75 17V7.692m10.447 2.61L20.25 7M12 15.9v5.6m-8.5-18l17 17");
}

</style>
