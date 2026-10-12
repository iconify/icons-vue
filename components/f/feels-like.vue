<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ttdy-b6jx"/><path class="q8odkmqvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feels-like" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q8odkmqvh {
  d: path("M2.75 21.25V19a4.25 4.25 0 0 1 8.5 0v2.25Zm13-7.65V5.75a2 2 0 0 1 4 0v7.85a3 3 0 1 1-4 0");
}

.ttdy-b6jx {
  cx: 7px;
  cy: 7.5px;
  r: 3px;
}

</style>
