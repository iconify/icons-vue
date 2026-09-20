<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="fx7anki8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:air-pressure-outline-bold" /></template>
<style>
.fx7anki8e {
  d: path("M12 16v-6");
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
