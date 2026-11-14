<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="scntx542r"/><path class="zu3a0rlzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gyroscope" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.scntx542r {
  d: path("M4 11a8 8 0 1 0 16 0a8 8 0 1 0-16 0m8-8.75V21.5m-3.5 0h7");
}

.zu3a0rlzi {
  d: path("M7 11a5 2.75 0 1 0 10 0a5 2.75 0 1 0-10 0");
}

</style>
