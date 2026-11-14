<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg1q37ame"/><path class="tjc4_6rhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hidden-disability-lanyard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rg1q37ame {
  d: path("m6 2.5l3.5 2.25h5L18 2.5m-6 2.25V7.5m-7 7a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

.tjc4_6rhs {
  d: path("M10.5 14.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m1.5-4h.01m3.99 4h.01m-4.01 4h.01M8 14.5h.01");
}

</style>
