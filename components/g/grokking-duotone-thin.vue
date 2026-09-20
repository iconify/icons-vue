<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5rxwxb6q"/><path class="vl3ktrutp"/><path class="qe97cg-lx"/><path class="qj99nibfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grokking-duotone-thin" /></template>
<style>
.e5rxwxb6q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.qj99nibfx {
  d: path("M6 18h8l4 -4V6");
}

.vl3ktrutp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 18h8l4 -4V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
