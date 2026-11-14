<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs8532b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chinese-takeout-box" /></template>
<style>
.vs8532b3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9h14l-2 11.5H7Zm0 0l2.5-3.5h9L19 9M8.5 5.5c0-2.75 7-2.75 7 0m-3.5 0V9");
}

</style>
