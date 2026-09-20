<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lo7kp72nh"/><path class="wmi7x3_7r"/><path class="m3koyfgfl"/><path class="pfndwmm4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handoff-outline-bold" /></template>
<style>
.lo7kp72nh {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.m3koyfgfl {
  d: path("M11 8h7");
}

.pfndwmm4f {
  d: path("m15 5 3 3 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wmi7x3_7r {
  d: path("M15 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
