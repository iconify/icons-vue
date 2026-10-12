<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g-vfy0b3u"/><path class="m-4gojuzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corkscrew" /></template>
<style>
.g-vfy0b3u {
  width: 16.5px;
  height: 3.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-4gojuzi {
  d: path("M12 6.25v3L15 11l-6 3.5l6 3.5l-3 1.75");
}

</style>
