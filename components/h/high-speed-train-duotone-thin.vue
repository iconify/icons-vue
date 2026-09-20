<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m_ivukb9u"/><path class="a3fayfb3t"/><path class="bcoat1b-j"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:high-speed-train-duotone-thin" /></template>
<style>
.a3fayfb3t {
  d: path("M2 18v-6l7 -7h9a2 2 0 0 1 2 2v11Z");
}

.bcoat1b-j {
  d: path("M9 12h11");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_ivukb9u {
  fill: currentColor;
  d: path("M2 18v-6l7 -7h9a2 2 0 0 1 2 2v11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
