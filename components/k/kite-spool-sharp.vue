<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc09fdb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kite-spool-sharp" /></template>
<style>
.yc09fdb7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 8h7.5v8h-7.5Zm1.25 2l5 4m-5 0l5-4m-9.75 2a1.75 6 0 1 0 3.5 0a1.75 6 0 1 0-3.5 0Zm11 0a1.75 6 0 1 0 3.5 0a1.75 6 0 1 0-3.5 0Zm-13 0h2m14.5 0h2");
}

</style>
