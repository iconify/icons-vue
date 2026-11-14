<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bfbh71elr"/><path class="wxjhkbc1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cottage-garden" /></template>
<style>
.bfbh71elr {
  d: path("M21.5 19.5h-19V10L7 5.5l4.5 4.5v9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wxjhkbc1i {
  d: path("M5.5 19.5V15h3v4.5m7.5 0v-6a1.5 1.5 0 0 1 0-3a1.5 1.5 0 0 1 0 3m4.5 6V8a1.5 1.5 0 0 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>
