<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xfo-vjbcz"/><path class="if5ft31dv"/><path class="ssjs9weax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-alarm-outline-bold" /></template>
<style>
.if5ft31dv {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ssjs9weax {
  d: path("M19 8c2 2 2 6 0 8");
}

.xfo-vjbcz {
  d: path("M6 17c2 -2 2 -5 2 -7 0 -3 2 -5 4 -5s4 2 4 5c0 2 0 5 2 7Z");
}

</style>
