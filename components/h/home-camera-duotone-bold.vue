<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m0ak0bcpt"/><path class="ceyqjyfpz"/><path class="wwrb2gbkc"/><path class="cj8gecc7a"/><path class="mmsmdzb7p"/><path class="dky0phbxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-camera-duotone-bold" /></template>
<style>
.ceyqjyfpz {
  fill: currentColor;
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cj8gecc7a {
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dky0phbxv {
  d: path("M19 11v7");
}

.m0ak0bcpt {
  fill: currentColor;
  d: path("M4 8v6h10V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mmsmdzb7p {
  d: path("M14 11h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wwrb2gbkc {
  d: path("M4 8v6h10V8Z");
}

</style>
