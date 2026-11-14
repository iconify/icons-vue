<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h23rbdd4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dotara" /></template>
<style>
.h23rbdd4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm4-11l-1-2.5h5l-1 2.5Zm0 0v13.5m3-13.5v13.5m-3.5 0h4");
}

</style>
