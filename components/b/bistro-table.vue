<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn6cogb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bistro-table" /></template>
<style>
.fn6cogb1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5a9 2 0 1 0 18 0A9 2 0 1 0 3 5Zm9 2v10.5M6.5 21q5.5 0 5.5-3.5q0 3.5 5.5 3.5");
}

</style>
