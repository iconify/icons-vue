<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3nxrfjzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contactless" /></template>
<style>
.e3nxrfjzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h13v10h-13Zm0 3.5h13m-1.5-7a3.5 3.5 0 0 1 3.5 3.5M14 3.25A6.75 6.75 0 0 1 20.75 10");
}

</style>
