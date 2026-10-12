<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lu9fy9npg"/><rect class="q11paq8vk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-thread" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lu9fy9npg {
  d: path("M2.75 5.75a2.5 2.5 0 0 1 2.5-2.5h8.5a2.5 2.5 0 0 1 2.5 2.5v3.5a2.5 2.5 0 0 1-2.5 2.5h-8.5a2.5 2.5 0 0 1-2.5-2.5Zm3.5 1.75h6.5M6.5 11.75v3.75a2 2 0 0 0 2 2h.75");
}

.q11paq8vk {
  width: 12px;
  height: 6.5px;
  x: 9.25px;
  y: 14.25px;
  rx: 2.5px;
}

</style>
