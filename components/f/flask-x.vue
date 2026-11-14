<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyu4pd41y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flask-x" /></template>
<style>
.dyu4pd41y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3h7M10 3v6L4.5 19.25q-.75 2.25 1.75 2.25h11.5q2.5 0 1.75-2.25L14 9V3m-3.75 11.25l3.5 3.5m0-3.5l-3.5 3.5");
}

</style>
