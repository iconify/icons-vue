<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h9piesnqy"/><path class="v34nbkq0p"/><path class="zmj1nccll"/><path class="q2pah9bya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-handout-duotone-thin" /></template>
<style>
.h9piesnqy {
  fill: currentColor;
  d: path("M8.5 10.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
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

.q2pah9bya {
  d: path("M20 15.33a3.5 3.5 0 1 1 -2.96 0");
}

.v34nbkq0p {
  d: path("M7 2.33a3.5 3.5 0 1 1 -2.96 0");
}

.zmj1nccll {
  d: path("M8.5 10.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
