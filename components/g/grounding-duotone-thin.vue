<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ptspw4g5a"/><path class="h05w6pb0b"/><path class="hosrnl1cs"/><path class="ymhw07_9a"/><path class="w-pek8c8r"/><path class="elc06ob4j"/><path class="l0v-b4kbr"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grounding-duotone-thin" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.elc06ob4j {
  d: path("M8 8h8");
}

.h05w6pb0b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hosrnl1cs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.ptspw4g5a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 2H5v15h14V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-pek8c8r {
  d: path("M14 2H5v15h14V7");
}

.ymhw07_9a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
