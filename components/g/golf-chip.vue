<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qk1idkihy"/><path class="i49ypkb8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-chip" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i49ypkb8u {
  d: path("M8 10.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0M6 16l-1-3.75M18 16l1-3.75");
}

.qk1idkihy {
  d: path("M2.5 18c3.5-5 15.5-5 19 0");
}

</style>
