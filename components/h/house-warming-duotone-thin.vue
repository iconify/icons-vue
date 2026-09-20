<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-yo_2b4g"/><path class="syw8dymcb"/><path class="rsz3y4a_c"/><path class="u-niy3p1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-warming-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-yo_2b4g {
  fill: currentColor;
  d: path("M4 19v-7l7 -7 7 7v7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rsz3y4a_c {
  d: path("M4 19v-7l7 -7 7 7v7Z");
}

.syw8dymcb {
  fill: currentColor;
  d: path("M11 16c-2 -1 -2 -4 0 -5 2 1 2 4 0 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u-niy3p1t {
  d: path("M11 16c-2 -1 -2 -4 0 -5 2 1 2 4 0 5");
}

</style>
