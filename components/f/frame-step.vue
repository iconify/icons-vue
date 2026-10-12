<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ijbb4wb5n"/><path class="y9z9b4k5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:frame-step" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijbb4wb5n {
  width: 12px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2px;
}

.y9z9b4k5z {
  d: path("M2.75 8.25h12m-12 7.5h12m3-7.25l3.5 3.5l-3.5 3.5");
}

</style>
