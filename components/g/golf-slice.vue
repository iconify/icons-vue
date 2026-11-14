<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="elhi6-c-i"/><path class="a2z5s4bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-slice" /></template>
<style>
.a2z5s4bbj {
  d: path("m14 3l2.5 2L14 7");
}

.elhi6-c-i {
  d: path("M9 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m2.5-5.75C9.5 9.5 8 5.5 16 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
