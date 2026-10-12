<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ttdy-b6jx"/><path class="so2m5-0so"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feels-like-sharp" /></template>
<style>
.so2m5-0so {
  d: path("M2.75 21.25V19a4.25 4.25 0 0 1 8.5 0v2.25Zm13-7.65V3.75h4v9.85a3 3 0 1 1-4 0Z");
}

.ttdy-b6jx {
  cx: 7px;
  cy: 7.5px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
