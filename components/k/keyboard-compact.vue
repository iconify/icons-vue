<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbnjc8b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keyboard-compact" /></template>
<style>
.nbnjc8b2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h19v13h-19Zm4 3.5h.01M10 9h.01m3.74 0h.01m3.74 0h.01M6.5 12.25h.01m3.49 0h.01m3.74 0h.01m3.74 0h.01M7.5 15.5h9");
}

</style>
