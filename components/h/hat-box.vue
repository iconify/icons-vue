<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uh6p4oaww"/><path class="me92lqvky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hat-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.me92lqvky {
  d: path("M2.5 6.5v3c0 1.75 3.75 3 8.5 3s8.5-1.25 8.5-3v-3M3.5 12v5.5c0 2.25 3.5 3.75 7.5 3.75q.21 0 .419-.005M18.5 12.65V12M14 20.25h8m-6.5 0v-3.5c0-1 .75-1.75 1.75-1.25l.75.5l.75-.5c1-.5 1.75.25 1.75 1.25v3.5");
}

.uh6p4oaww {
  d: path("M2.5 6.5a8.5 3 0 1 0 17 0a8.5 3 0 1 0-17 0");
}

</style>
