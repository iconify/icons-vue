<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y596qf_hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crop-loss" /></template>
<style>
.y596qf_hz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.5v-17M8 19c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4Zm0 0c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4Zm0-6.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4Zm0 0c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4Zm10 2v7m-3-3l3 3l3-3");
}

</style>
