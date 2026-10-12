<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="c4diszbug"/><path class="lycgwgkxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bar-stools" /></template>
<style>
.c4diszbug {
  width: 11.5px;
  height: 3.5px;
  x: 6.25px;
  y: 3.75px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lycgwgkxh {
  d: path("m8.25 7.25l-2 14m9.5-14l2 14M7 16h10");
}

</style>
