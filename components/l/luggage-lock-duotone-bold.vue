<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d8golhb-x"/><path class="c07le3bhf"/><path class="lhtxwmluz"/><path class="ataf5kbyl"/><path class="y1lnycw3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:luggage-lock-duotone-bold" /></template>
<style>
.ataf5kbyl {
  d: path("M7.5 10a4.5 4.5 0 0 1 9 0");
}

.c07le3bhf {
  fill: currentColor;
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d8golhb-x {
  fill: currentColor;
  d: path("M5 12a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lhtxwmluz {
  d: path("M5 12a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y1lnycw3l {
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
