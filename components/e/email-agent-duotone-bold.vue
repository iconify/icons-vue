<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7689ssil"/><path class="cf6epupol"/><path class="rmp_51owx"/><path class="pfe6vjb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:email-agent-duotone-bold" /></template>
<style>
.cf6epupol {
  d: path("M7.5 2.83a3.5 3.5 0 1 1 -2.96 0");
}

.h7689ssil {
  fill: currentColor;
  d: path("M10 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pfe6vjb3x {
  d: path("m12 12 3.5 3.5L19 12");
}

.rmp_51owx {
  d: path("M10 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
