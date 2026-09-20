<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wl0ht0yem"/><path class="fim5wvb3d"/><path class="j5z_xpbsk"/><path class="lhhiiffss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:active-active-outline-bold" /></template>
<style>
.fim5wvb3d {
  d: path("M5.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.j5z_xpbsk {
  d: path("M13.5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.lhhiiffss {
  d: path("M16.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wl0ht0yem {
  d: path("M2.5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
