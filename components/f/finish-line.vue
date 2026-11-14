<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjchvubkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:finish-line" /></template>
<style>
.jjchvubkc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.5V3M2.5 21.5h5m11.5 0V3m-2.5 18.5h5M5 9q7 3.5 14 0M5 3l4.5 1.75L5 6.5Z");
}

</style>
