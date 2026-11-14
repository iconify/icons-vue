<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dj5-btbgj"/><path class="xkwdavw4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:foul-weather-jacket" /></template>
<style>
.dj5-btbgj {
  d: path("M8.5 6L5 7.5C4 8 3.5 9 3.25 10l-.75 7h3v4.5h13V17h3l-.75-7C20.5 9 20 8 19 7.5L15.5 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xkwdavw4u {
  d: path("M8.5 9.5V6a3.5 3.5 0 0 1 7 0v3.5q-3.5 1.5-7 0m3.5.75V21.5");
}

</style>
