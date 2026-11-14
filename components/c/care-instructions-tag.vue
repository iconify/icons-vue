<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tbs6iskbf"/><path class="w0cg4fb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:care-instructions-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tbs6iskbf {
  d: path("M5.125 5.5h13.75A2.625 2.625 0 0 1 21.5 8.125v7.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 15.875v-7.75A2.625 2.625 0 0 1 5.125 5.5m1.375 0v13M4.5 8h.01m-.01 4h.01m-.01 4h.01");
}

.w0cg4fb3i {
  d: path("M8.75 16H19c0-2.25-1-3.75-3-3.75h-4.75c-1.5.5-2.25 2-2.5 3.75M12 12.25c0-2.25.75-3 2.25-3H17v3");
}

</style>
