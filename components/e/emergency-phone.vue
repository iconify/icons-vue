<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="c7dsb1bzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emergency-phone" /></template>
<style>
.a_-q_pb0z {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

.c7dsb1bzl {
  d: path("M7 7.5h2l1 2.75l-1.5 1A7.5 7.5 0 0 0 12.25 15l1-1.5l2.75 1v2a1.5 1.5 0 0 1-1.5 1.5a10 10 0 0 1-9-9A1.5 1.5 0 0 1 7 7.5m9-1.75v4.5M13.75 8h4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
