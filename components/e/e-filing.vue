<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-uopbb1a"/><path class="hp7vvkb0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:e-filing" /></template>
<style>
.f-uopbb1a {
  d: path("M6.625 4.75h10.75A2.625 2.625 0 0 1 20 7.375v5.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 13.125v-5.75A2.625 2.625 0 0 1 6.625 4.75M2.5 19.25h19M7 8.75h4M7 13h4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hp7vvkb0t {
  d: path("M13.5 9.5L15 11l2.25-3");
}

</style>
