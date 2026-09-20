<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="acyg6nb1v"/><path class="ctdwryy5l"/><path class="d5_p0tpur"/><path class="ciwbnxb_b"/><path class="jnysnpbhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fork-outline-bold" /></template>
<style>
.acyg6nb1v {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ciwbnxb_b {
  d: path("M3 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ctdwryy5l {
  d: path("M10.5 9.5 6 14");
}

.d5_p0tpur {
  d: path("M13.5 9.5 18 14");
}

.jnysnpbhj {
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
