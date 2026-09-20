<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n36352b2b"/><path class="j3g0obcgt"/><path class="m_ifpmwzr"/><path class="w-c31ggft"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:city-break-outline-bold" /></template>
<style>
.j3g0obcgt {
  d: path("M13 21V4h6v17");
}

.m_ifpmwzr {
  d: path("M4 12h6");
}

.n36352b2b {
  d: path("M4 21V8h6v13");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w-c31ggft {
  d: path("M13 9h6");
}

</style>
