<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="azrd_nbzs"/><path class="unbhqgb5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:acne" /></template>
<style>
.azrd_nbzs {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM9 11h.01M15 11h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unbhqgb5f {
  d: path("M10 16q2 1.25 4 0M8.75 6.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm4.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm3 7.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
