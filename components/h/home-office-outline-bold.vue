<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m2rbp207a"/><path class="rrzohjbez"/><path class="l8dn9jbyp"/><path class="yfv778qvg"/><path class="bg9lr2bcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-office-outline-bold" /></template>
<style>
.bg9lr2bcw {
  d: path("M20 15v6");
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.m2rbp207a {
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.rrzohjbez {
  d: path("M12 12v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yfv778qvg {
  d: path("M4 15v6");
}

</style>
