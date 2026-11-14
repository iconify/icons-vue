<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ccrce8luq"/><path class="u4uwt6bgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boat-dealer" /></template>
<style>
.ccrce8luq {
  d: path("M2.5 9H17l4.5-2.5l-2.75 6.5q-.5 1.5-2 1.5H5.25Q4 14.5 3.5 13Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u4uwt6bgs {
  d: path("M6 9V5.5h6L14.5 9m-7 5.5v5m8-5v5m-12 0h16");
}

</style>
