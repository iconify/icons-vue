<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tjmqpacvo"/><rect class="er8xuq0mh"/><path class="cj3-e79pp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laptop-and-smartwatch" /></template>
<style>
.cj3-e79pp {
  d: path("M18.5 13.25V11.5m0 6.75V20");
}

.er8xuq0mh {
  width: 5.5px;
  height: 5px;
  x: 15.75px;
  y: 13.25px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tjmqpacvo {
  d: path("M5.75 3h12q2 0 2 2v2q0 2-2 2h-3q-2 0-2 2v1q0 2-2 2h-5q-2 0-2-2V5q0-2 2-2m-3 14.25h10");
}

</style>
