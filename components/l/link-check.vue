<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fizbfccrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:link-check" /></template>
<style>
.fizbfccrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5H7.5a4.5 4.5 0 0 0 0 9H9m6-9h1.5A4.5 4.5 0 0 1 21 10M8.5 10h7m-.75 8l2 2L21 15.75");
}

</style>
