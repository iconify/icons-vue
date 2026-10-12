<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rxlus3b-x"/><path class="g8-uwvbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-right-up" /></template>
<style>
.g8-uwvbdc {
  d: path("m11 8.5l3.75-3.75L18.5 8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rxlus3b-x {
  d: path("M4.25 19.75h8a2.5 2.5 0 0 0 2.5-2.5V4.75");
}

</style>
