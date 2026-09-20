<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c7os3sb0q"/><path class="caalqdcke"/><path class="jzln5b9mk"/><path class="eujto1cse"/><path class="m3i8kpzkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:counsellor-duotone-bold" /></template>
<style>
.c7os3sb0q {
  fill: currentColor;
  d: path("M4 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.caalqdcke {
  fill: currentColor;
  d: path("M13 4h8a1 1 0 0 1 1 1v6a1 1 0 0 1 -1 1h-5l-3 3v-3a1 1 0 0 1 -1 -1V5a1 1 0 0 1 1 -1");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eujto1cse {
  d: path("M2.5 18a4.5 4.5 0 0 1 9 0");
}

.jzln5b9mk {
  d: path("M4 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.m3i8kpzkt {
  d: path("M13 4h8a1 1 0 0 1 1 1v6a1 1 0 0 1 -1 1h-5l-3 3v-3a1 1 0 0 1 -1 -1V5a1 1 0 0 1 1 -1");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
