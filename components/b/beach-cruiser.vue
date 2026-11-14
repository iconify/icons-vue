<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f1bj4nb4e"/><path class="py5-wbsfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beach-cruiser" /></template>
<style>
.f1bj4nb4e {
  d: path("M2.5 14.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py5-wbsfx {
  d: path("M6.5 14.5H11q2-5.5 4.5-6l2 6M7.5 8h3M9 8l-2.5 6.5m9-6l.5-3q-1.5-.5-3.25.5");
}

</style>
