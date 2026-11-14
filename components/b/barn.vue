<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n2jh8ls7s"/><path class="dai76bdum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barn" /></template>
<style>
.dai76bdum {
  d: path("M8 13.5h8V21H8Zm0 0l8 7.5m0-7.5L8 21m2.5-14h3v3h-3Z");
}

.n2jh8ls7s {
  d: path("m3.5 11l3-5.5L12 3l5.5 2.5l3 5.5v10h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
