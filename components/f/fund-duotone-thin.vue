<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vq4q60_me"/><path class="x3p8m6bwl"/><path class="ccg2ab48o"/><path class="vo1-lv2pt"/><path class="oz3eccbug"/><path class="ru1rctb5n"/><path class="f9cgo8b6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fund-duotone-thin" /></template>
<style>
.ccg2ab48o {
  fill: currentColor;
  d: path("M13.5 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f9cgo8b6s {
  d: path("M13.5 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oz3eccbug {
  d: path("M7 8a5 5 0 0 1 10 0");
}

.ru1rctb5n {
  d: path("M6.5 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vo1-lv2pt {
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.vq4q60_me {
  fill: currentColor;
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x3p8m6bwl {
  fill: currentColor;
  d: path("M6.5 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
