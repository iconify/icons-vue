<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ef-jgqbdk"/><path class="k4p4tzbhq"/><path class="y_j9zzqtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lock-door-outline-bold" /></template>
<style>
.ef-jgqbdk {
  d: path("M4 3v18h10V3Z");
}

.k4p4tzbhq {
  d: path("M17 13v6h5v-6Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y_j9zzqtv {
  d: path("M17.5 13a2 2 0 0 1 4 0");
}

</style>
