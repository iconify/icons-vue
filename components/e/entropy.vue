<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv_rhvbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:entropy" /></template>
<style>
.tv_rhvbli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h4.25v4.25H3Zm0 7h4.25v4.25H3Zm0 7h4.25v4.25H3Zm12.25-9.25l-4-1.5l1.5-4l4 1.5Zm2 7l4-1.5l-1.5-4l-4 1.5Zm-3.75.5l3 3l-3 3l-3-3Z");
}

</style>
