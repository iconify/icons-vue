<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m_khuob7g"/><path class="bu26n5xpc"/><rect class="yjqautbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flag-pole" /></template>
<style>
.bu26n5xpc {
  d: path("M6 8.75c2.5-1.25 4.25-1.25 6.75 0s4.25 1.25 6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_khuob7g {
  d: path("M6 2.75V18.5M6 5.25C8.5 4 10.25 4 12.75 5.25s4.25 1.25 6.5 0v7c-2.25 1.25-4 1.25-6.5 0S8.5 11 6 12.25Z");
}

.yjqautbck {
  width: 5px;
  height: 2.75px;
  x: 3.5px;
  y: 18.5px;
  rx: 1px;
}

</style>
