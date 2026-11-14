<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj7qqxx3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invertebrate" /></template>
<style>
.hj7qqxx3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13V9.5a5.5 5.5 0 0 1 11 0V13Zm2 0c0 5-2.5 7-5 6m8.5-6v8.5m3.5-8.5c0 5 2.5 7 5 6");
}

</style>
