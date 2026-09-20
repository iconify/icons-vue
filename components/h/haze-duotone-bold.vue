<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gap0lacnb"/><path class="c5v_de02i"/><path class="yih0nfb7c"/><path class="miurf-h0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:haze-duotone-bold" /></template>
<style>
.c5v_de02i {
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.gap0lacnb {
  fill: currentColor;
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.miurf-h0g {
  d: path("M5 18h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yih0nfb7c {
  d: path("M3 14h18");
}

</style>
