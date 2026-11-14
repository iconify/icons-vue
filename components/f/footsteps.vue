<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0-o5vbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:footsteps" /></template>
<style>
.c0-o5vbxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12a3 4 0 1 0 6 0a3 4 0 1 0-6 0Zm1 8.25a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Zm8-13.75a3 4 0 1 0 6 0a3 4 0 1 0-6 0Zm1 8.25a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Z");
}

</style>
