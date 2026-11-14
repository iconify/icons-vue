<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dy1yp9btx"/><path class="xfnru_bvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coach-whistle" /></template>
<style>
.dy1yp9btx {
  d: path("M3 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfnru_bvw {
  d: path("m13 11.5l8-3V12l-7 2.25M7 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM8.5 3.5V6");
}

</style>
