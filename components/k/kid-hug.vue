<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qwenqmlcr"/><path class="c6cn0gb7i"/><path class="zxtkb6xdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kid-hug" /></template>
<style>
.c6cn0gb7i {
  d: path("M10 20.5c0-3.027 1.432-5.195 3.646-6.071");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qwenqmlcr {
  d: path("M5 7a2.75 2.75 0 1 0 5.5 0A2.75 2.75 0 1 0 5 7m8.5 0A2.75 2.75 0 1 0 19 7a2.75 2.75 0 1 0-5.5 0m-11 13.5C2.5 16.5 5 14 8 14c1.5 0 2.75.75 3.75 1.75");
}

.zxtkb6xdc {
  d: path("M10.25 19.5C8.75 18.25 7 18.25 5.5 19m13 2.5l-3-3a2 2 0 0 1 3-2.5a2 2 0 0 1 3 2.5Z");
}

</style>
