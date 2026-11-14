<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ruyt_r40r"/><path class="g46q1ac-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lacrosse-ball" /></template>
<style>
.g46q1ac-i {
  d: path("M10 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ruyt_r40r {
  d: path("M8.5 13L6 6c-.5-2.5 1.5-3.5 4-3.5h4.5c3 0 4.5 2 3.5 4.5l-4.5 6Zm2.5 0l4 8.5");
}

</style>
