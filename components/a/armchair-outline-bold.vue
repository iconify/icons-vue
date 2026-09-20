<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xm60vxbgs"/><path class="ys-dg812g"/><path class="q1cfkyb_k"/><path class="hhn28yosy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:armchair-outline-bold" /></template>
<style>
.hhn28yosy {
  d: path("M21 20v-8h-4");
}

.q1cfkyb_k {
  d: path("M3 20v-8h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xm60vxbgs {
  d: path("M7 16V5h10v11");
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
