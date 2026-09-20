<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwwvkoo2y"/><path class="hh9110min"/><path class="r9wazo8vh"/><path class="nbsh9vihc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cache-hit-duotone-thin" /></template>
<style>
.hh9110min {
  d: path("M4 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbsh9vihc {
  d: path("m16 16 3.5 3.5");
}

.nwwvkoo2y {
  fill: currentColor;
  d: path("M4 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r9wazo8vh {
  d: path("M13 6.5 9.5 10H12l-3.5 3.5");
}

</style>
