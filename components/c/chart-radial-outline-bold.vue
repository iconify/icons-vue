<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m5e7pz7_z"/><path class="n6apnpbtf"/><path class="cs--63jny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-radial-outline-bold" /></template>
<style>
.cs--63jny {
  d: path("M12 2a10 10 0 1 1 -7.07 2.93");
}

.m5e7pz7_z {
  d: path("M12 8a4 4 0 0 1 0 8");
}

.n6apnpbtf {
  d: path("M12 5a7 7 0 1 1 -7 7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
