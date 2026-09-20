<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m8c8atiya"/><path class="n0n63pb2v"/><path class="meb7wcbot"/><path class="o40l0bbgl"/><path class="g45hqpb0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hierarchical-memory-duotone-bold" /></template>
<style>
.g45hqpb0s {
  d: path("M10.5 12h3");
}

.m8c8atiya {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.meb7wcbot {
  d: path("M7 5h10");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.o40l0bbgl {
  d: path("M9 8.5h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
