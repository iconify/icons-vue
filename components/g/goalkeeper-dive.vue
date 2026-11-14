<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jk0w8jbxt"/><path class="kv1bx1bnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:goalkeeper-dive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jk0w8jbxt {
  d: path("m16 8l-6 4l-4.5 3.5l-2.5 4m2.5-4l2.5 4M5.5 8A1.75 1.75 0 1 0 9 8a1.75 1.75 0 1 0-3.5 0");
}

.kv1bx1bnr {
  d: path("M15.5 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
