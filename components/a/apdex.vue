<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yppkxqfsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apdex" /></template>
<style>
.yppkxqfsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.75a9.5 9.5 0 0 1 3.143-7.06m2.493-1.619a9.5 9.5 0 0 1 7.728 0m2.493 1.619a9.5 9.5 0 0 1 3.143 7.06m-11.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.5-1.5l3-3");
}

</style>
