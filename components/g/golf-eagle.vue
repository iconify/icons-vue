<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im6fp9bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-eagle" /></template>
<style>
.im6fp9bts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 9L2.5 4.5l2 5l6 2.5v1.5l-1.5 3h6l-1.5-3V12l6-2.5l2-5L13.25 9V7l1.25-.75L13 5a1.25 1.25 0 0 0-2.25 1Zm6.75 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
