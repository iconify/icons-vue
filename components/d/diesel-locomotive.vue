<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mow_f5l_u"/><path class="ywz1pjbqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diesel-locomotive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mow_f5l_u {
  d: path("M2.5 17V5A1.5 1.5 0 0 1 4 3.5h6v5h10a1.5 1.5 0 0 1 1.5 1.5v7Z");
}

.ywz1pjbqc {
  d: path("M5.5 3.5v5H10m5 0v-3M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
