<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-ff8v3ql"/><path class="six-1tb5w"/><path class="vcvfzbc_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-rolling" /></template>
<style>
.g-ff8v3ql {
  d: path("M6 10.5h6a3.5 3.5 0 0 1 3.5 3.5v2.5A3.5 3.5 0 0 1 12 20H6a3.5 3.5 0 0 1-3.5-3.5V14A3.5 3.5 0 0 1 6 10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.six-1tb5w {
  d: path("m16.577 12.551l2.5-1.041a1.75 1.75 0 0 1 2.423 1.615v3.75a1.75 1.75 0 0 1-2.423 1.615l-2.5-1.041a1.75 1.75 0 0 1-1.077-1.616v-1.666a1.75 1.75 0 0 1 1.077-1.616M2.5 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m7 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.vcvfzbc_t {
  d: path("M5 6.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m7 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
