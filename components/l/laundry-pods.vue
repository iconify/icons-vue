<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ls46fcc7l"/><path class="a9rboj3-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laundry-pods" /></template>
<style>
.a9rboj3-u {
  d: path("M2.75 8.25a2.25 2.25 0 0 1 4.5 0a2.25 2.25 0 0 0 4.5 0m.5 7.5a2.25 2.25 0 0 1 4.5 0a2.25 2.25 0 0 0 4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ls46fcc7l {
  d: path("M2.75 8.25a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m9.5 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
