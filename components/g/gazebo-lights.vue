<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j2vtdjb2b"/><path class="hcg1-8g8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gazebo-lights" /></template>
<style>
.hcg1-8g8o {
  fill: currentColor;
  d: path("M7.25 15.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM11 16a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm3.75-.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.j2vtdjb2b {
  d: path("M2.5 9L12 3l9.5 6Zm2 0v12m15-12v12m-15-9.5q7.5 6.5 15 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
