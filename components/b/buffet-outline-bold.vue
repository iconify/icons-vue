<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zugrvnb7t"/><path class="e325robmt"/><path class="bfcwd7bcm"/><path class="v7ifz5bvw"/><path class="leijmjbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:buffet-outline-bold" /></template>
<style>
.bfcwd7bcm {
  d: path("M13 13a4 4 0 0 1 8 0");
}

.e325robmt {
  d: path("M3 13a4 4 0 0 1 8 0");
}

.leijmjbkg {
  d: path("M18 13v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v7ifz5bvw {
  d: path("M6 13v6");
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
