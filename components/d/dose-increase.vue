<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj8pc7b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dose-increase" /></template>
<style>
.kj8pc7b0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3.5h4A1.25 1.25 0 0 1 10 4.75v14.5a1.25 1.25 0 0 1-1.25 1.25h-4a1.25 1.25 0 0 1-1.25-1.25V4.75A1.25 1.25 0 0 1 4.75 3.5Zm12 17V4m-3.5 3.5l3.5-3.5l3.5 3.5M3.5 12H10");
}

</style>
