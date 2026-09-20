<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3q_wpbez"/><path class="f23oww7ng"/><path class="yz8w-bcjg"/><path class="y8cxqebzo"/><path class="ob3bf9b2i"/><path class="r4bxr4bnm"/><path class="ljz_vjbfq"/><path class="phj3jm8ef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:label-queue-duotone-thin" /></template>
<style>
.f23oww7ng {
  fill: currentColor;
  d: path("M5 14h10l3.5 3.5L15 21H5Z");
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

.ljz_vjbfq {
  d: path("M7 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ob3bf9b2i {
  d: path("M5 3h10l3.5 3.5L15 10H5Z");
}

.phj3jm8ef {
  d: path("M7 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.r4bxr4bnm {
  d: path("M5 14h10l3.5 3.5L15 21H5Z");
}

.y3q_wpbez {
  fill: currentColor;
  d: path("M5 3h10l3.5 3.5L15 10H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y8cxqebzo {
  fill: currentColor;
  d: path("M7 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yz8w-bcjg {
  fill: currentColor;
  d: path("M7 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
