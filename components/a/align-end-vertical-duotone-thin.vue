<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h6ny9xb7b"/><path class="ll9bnb1gg"/><path class="f3r6jjb4a"/><path class="q7xe92bpy"/><path class="camhvtqcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-end-vertical-duotone-thin" /></template>
<style>
.camhvtqcl {
  d: path("M11 14h6v4h-6Z");
}

.f3r6jjb4a {
  d: path("M20 3v18");
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

.ll9bnb1gg {
  fill: currentColor;
  d: path("M11 14h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q7xe92bpy {
  d: path("M7 7h10v4H7Z");
}

</style>
