<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yhswpf2nj"/><path class="qarcjib7d"/><path class="z1gyoabnz"/><path class="n708z7b3q"/><path class="ia7llpjvs"/><path class="edletn6ej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-heatmap-outline-bold" /></template>
<style>
.edletn6ej {
  d: path("M15.5 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ia7llpjvs {
  d: path("M5.5 7.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n708z7b3q {
  d: path("M14 16a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.qarcjib7d {
  d: path("M14 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yhswpf2nj {
  d: path("M4 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.z1gyoabnz {
  d: path("M4 16a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
