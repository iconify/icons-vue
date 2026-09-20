<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yirjebbnv"/><path class="j3wu6pb4g"/><path class="y0jjn0phn"/><path class="yazo7scbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:acorn-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3wu6pb4g {
  d: path("M6 9a6 6 0 0 0 12 0Z");
}

.y0jjn0phn {
  d: path("M7 9a5 5 0 0 0 5 10 5 5 0 0 0 5 -10");
}

.yazo7scbq {
  d: path("M12 3v3");
}

.yirjebbnv {
  fill: currentColor;
  d: path("M6 9a6 6 0 0 0 12 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
