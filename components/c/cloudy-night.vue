<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhcam0b6w"/><path class="jz9sj9chv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloudy-night" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jz9sj9chv {
  d: path("M9 13a7 7 0 0 1 6-8.5A7.5 7.5 0 0 0 6 16");
}

.zhcam0b6w {
  d: path("M9 19h9a3.5 3.5 0 0 0 0-7a5 5 0 0 0-9 1a3 3 0 0 0 0 6");
}

</style>
