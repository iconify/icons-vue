<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyc-hwuap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ladderway" /></template>
<style>
.qyc-hwuap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5V19m7-16.5V19m-7-16.5h7m-7 2.75h7M8.5 8h7m-7 2.75h7m-7 2.75h7M2.5 19a9.5 2.75 0 1 0 19 0a9.5 2.75 0 1 0-19 0Z");
}

</style>
