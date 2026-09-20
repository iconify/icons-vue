<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oh4p-ccfe"/><path class="x6pm5hl4u"/><path class="lldlp5blb"/><path class="b603-acaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inline-alert-outline-bold" /></template>
<style>
.b603-acaz {
  d: path("M10 12h8");
}

.lldlp5blb {
  d: path("M5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.oh4p-ccfe {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x6pm5hl4u {
  d: path("M6 10v2.5");
}

</style>
