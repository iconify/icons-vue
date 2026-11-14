<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnagu2jcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dustpan-brush" /></template>
<style>
.xnagu2jcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21H12l-1.75-7.5h-6Zm4.75-7.5V8m11-5.5v6m-3 0h6V12h-6Zm.5 3.5L15 21h6.5l-.75-9");
}

</style>
