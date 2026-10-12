<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcuc5fbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lassi-glass-sharp" /></template>
<style>
.dcuc5fbhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 9.25h9.5L15.6 20.1l-.093 1.154l-1.157-.004h-4.7l-1.157.004L8.4 20.1Zm-.5 0a2 2 0 0 1 2-3a2.75 2.75 0 0 1 5.25-.5a2.2 2.2 0 0 1 3.25 3.5Zm1.75 4h7");
}

</style>
