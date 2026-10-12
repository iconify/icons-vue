<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="q71tojf4b"/><rect class="ukv1vgn5n"/><path class="e5khnbbpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:avatar-astronaut" /></template>
<style>
.e5khnbbpy {
  d: path("M5 21.25h14a1 1 0 0 0 1-1c0-2.6-3.6-4-8-4s-8 1.4-8 4a1 1 0 0 0 1 1m5.5-2.5h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q71tojf4b {
  cx: 12px;
  cy: 8.25px;
  r: 5.5px;
}

.ukv1vgn5n {
  width: 6.5px;
  height: 4.5px;
  x: 8.75px;
  y: 6px;
  rx: 2.25px;
}

</style>
