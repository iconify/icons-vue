<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m8c8atiya"/><path class="wmn-8gkkk"/><path class="n0n63pb2v"/><path class="nrad3_umv"/><path class="gib7r1bvf"/><path class="u41hfsjfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-escrow-duotone-regular" /></template>
<style>
.gib7r1bvf {
  d: path("M12 9.5V12");
}

.m8c8atiya {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.nrad3_umv {
  d: path("M10 7.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u41hfsjfh {
  d: path("M12 10.5h2.5");
}

.wmn-8gkkk {
  fill: currentColor;
  d: path("M10 7.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
