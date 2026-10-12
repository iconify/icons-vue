<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jwu2s8bzx"/><path class="gyh3r2biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fertilizer-bag" /></template>
<style>
.gyh3r2biy {
  d: path("M4.5 6.5h15m-11 11c0-4.5 2.5-7.5 7-8c.25 4.75-2.25 7.75-7 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwu2s8bzx {
  width: 15px;
  height: 18.5px;
  x: 4.5px;
  y: 2.75px;
  rx: 2px;
}

</style>
