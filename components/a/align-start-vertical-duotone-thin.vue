<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h6ny9xb7b"/><path class="s409al4ya"/><path class="crv4i00bu"/><path class="q7xe92bpy"/><path class="w329m1boj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-start-vertical-duotone-thin" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.h6ny9xb7b {
  fill: currentColor;
  d: path("M7 7h10v4H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7xe92bpy {
  d: path("M7 7h10v4H7Z");
}

.s409al4ya {
  fill: currentColor;
  d: path("M7 14h6v4H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w329m1boj {
  d: path("M7 14h6v4H7Z");
}

</style>
