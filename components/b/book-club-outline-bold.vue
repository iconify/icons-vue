<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k_vbx2s0e"/><path class="jlme50m5v"/><path class="je7q13b0j"/><path class="nsr-ek9xa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:book-club-outline-bold" /></template>
<style>
.je7q13b0j {
  d: path("M3 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.jlme50m5v {
  d: path("M9 10v11");
}

.k_vbx2s0e {
  d: path("M6 12a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.nsr-ek9xa {
  d: path("M15 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
