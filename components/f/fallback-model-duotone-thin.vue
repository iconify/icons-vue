<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q4v8xtb_n"/><path class="y57qu4bjp"/><path class="sk4_mtx5w"/><path class="nimx5w1ex"/><path class="w5z_myj4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fallback-model-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nimx5w1ex {
  d: path("M12 11.5V16");
}

.q4v8xtb_n {
  fill: currentColor;
  d: path("M12 2.5 16.5 7 12 11.5 7.5 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sk4_mtx5w {
  d: path("M12 2.5 16.5 7 12 11.5 7.5 7Z");
}

.w5z_myj4u {
  d: path("m12 16 2.5 2.5L12 21l-2.5 -2.5Z");
}

.y57qu4bjp {
  fill: currentColor;
  d: path("m12 16 2.5 2.5L12 21l-2.5 -2.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
