<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="witkf1bpe"/><path class="fbfjil0zf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:court-recording" /></template>
<style>
.fbfjil0zf {
  d: path("M3.5 10a6 6 0 0 0 12 0m-6 6v4.5m-3 0h6m3-2a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.witkf1bpe {
  d: path("M7.5 2.5h4A1.5 1.5 0 0 1 13 4v7a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 6 11V4a1.5 1.5 0 0 1 1.5-1.5Z");
}

</style>
