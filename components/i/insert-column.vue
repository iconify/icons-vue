<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e7ezedc6p"/><path class="yc5bn4bjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insert-column" /></template>
<style>
.e7ezedc6p {
  width: 11px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc5bn4bjk {
  d: path("M8.25 8.25v13m-5.5-13h11m-11 6.5h11m5.125-5.125v4.75M16.5 12h4.75");
}

</style>
