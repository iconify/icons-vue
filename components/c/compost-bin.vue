<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbtka1bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compost-bin" /></template>
<style>
.vbtka1bwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h15L17 21.5H5Zm8.5 0l8.5-5M6 10c0-3.5 2-6 5.5-6.5c0 3.5-2 6-5.5 6.5Z");
}

</style>
