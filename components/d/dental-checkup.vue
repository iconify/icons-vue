<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c-edibknc"/><path class="m2sffu8jk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-checkup" /></template>
<style>
.c-edibknc {
  d: path("M10 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0m1.5 3.5l-8 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2sffu8jk {
  d: path("M12.75 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m2 10.5l2 2L21 15.75");
}

</style>
