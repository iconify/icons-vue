<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ugdbidcqi"/><path class="l0v-b4kbr"/><path class="az5esj3_g"/><path class="d_yxl29go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handoff-shift-outline-bold" /></template>
<style>
.az5esj3_g {
  d: path("M10.5 9.5 8 12l2.5 2.5");
}

.d_yxl29go {
  d: path("M13.5 9.5 16 12l-2.5 2.5");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

</style>
