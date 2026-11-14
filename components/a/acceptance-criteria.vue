<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pd8gp4zrk"/><path class="kiux9accd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:acceptance-criteria" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kiux9accd {
  d: path("M6.5 12.5L8 14l2.5-2.5m2.5 1.25h4.5M6.5 17L8 18.5l2.5-2.5");
}

.pd8gp4zrk {
  d: path("M7.875 3h8.25A4.375 4.375 0 0 1 20.5 7.375v9.25A4.375 4.375 0 0 1 16.125 21h-8.25A4.375 4.375 0 0 1 3.5 16.625v-9.25A4.375 4.375 0 0 1 7.875 3M3.5 8h17");
}

</style>
