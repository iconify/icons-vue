<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5br__bzy"/><path class="i4b1r2bjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:circle-hook" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4b1r2bjy {
  d: path("M8 7v8a5 5 0 1 0 3.25-4.75l-.25 3");
}

.x5br__bzy {
  d: path("M6 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
