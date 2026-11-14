<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="am7r16bpz"/><path class="e5tn9ybnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coal-bucket" /></template>
<style>
.am7r16bpz {
  d: path("M6.718 9.5h10.564a1.5 1.5 0 0 1 1.486 1.703l-1.091 8a1.5 1.5 0 0 1-1.486 1.297H7.809a1.5 1.5 0 0 1-1.486-1.297l-1.091-8A1.5 1.5 0 0 1 6.718 9.5M5 9.5C5 2 19 2 19 9.5");
}

.e5tn9ybnp {
  d: path("m8 9.5l2-2l2 1.25l2.5-1.5L16 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
