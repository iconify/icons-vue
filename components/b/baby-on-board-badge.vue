<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r-dlkvbtq"/><path class="mub6d7n-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-on-board-badge" /></template>
<style>
.mub6d7n-q {
  d: path("M10.5 9.5v-2a1.5 1.5 0 0 1 3 0v2m-4.75 0v7a1.5 1.5 0 0 0 1.5 1.5h3.5a1.5 1.5 0 0 0 1.5-1.5v-7m-3 3.75h3");
}

.r-dlkvbtq {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM8 9.5h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
