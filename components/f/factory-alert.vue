<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl2cpccuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:factory-alert" /></template>
<style>
.bl2cpccuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.959 18H2.5V8.5L6.75 4v4.5L11 4v4.5L15.25 4v4.5L19.5 4v7.341m-2 2.159l4 7.5h-8Zm0 3.5v1.75");
}

</style>
