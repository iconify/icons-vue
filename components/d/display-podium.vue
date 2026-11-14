<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z7scqubjs"/><path class="m3qvxmcts"/><path class="p404z1n9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:display-podium" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m3qvxmcts {
  d: path("M4 13.5a8 2.75 0 1 0 16 0a8 2.75 0 1 0-16 0");
}

.p404z1n9w {
  d: path("M9 3h6a1.5 1.5 0 0 1 1.5 1.5V10a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 10V4.5A1.5 1.5 0 0 1 9 3M7.5 6h9M12 3v3");
}

.z7scqubjs {
  d: path("M4 13.5v5a8 2.75 0 0 0 16 0v-5");
}

</style>
