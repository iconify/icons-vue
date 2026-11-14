<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dc9u28bnu"/><path class="a91r23v4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bin-bags-roll" /></template>
<style>
.a91r23v4r {
  d: path("M5.5 2.75h13a2.5 3.75 0 0 1 0 7.5h-13m5 4.75c-4 1-4.5 6.5-1 6.5h5c3.5 0 3-5.5-1-6.5Zm-5-8.5h.01M9.5 13l2.5 2l2.5-2");
}

.dc9u28bnu {
  d: path("M3 6.5a2.5 3.75 0 1 0 5 0a2.5 3.75 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
