<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gu-z1pqiw"/><path class="kyd26-b5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bread-maker" /></template>
<style>
.gu-z1pqiw {
  d: path("M6.875 4.5h10.25A4.375 4.375 0 0 1 21.5 8.875v6.75A4.375 4.375 0 0 1 17.125 20H6.875A4.375 4.375 0 0 1 2.5 15.625v-6.75A4.375 4.375 0 0 1 6.875 4.5M2.5 7.5h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kyd26-b5q {
  d: path("M7.5 16.5V14a4.5 3.5 0 0 1 9 0v2.5Z");
}

</style>
