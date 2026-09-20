<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pywr_yykw"/><path class="m0hvambgh"/><path class="tl2fjsrpp"/><path class="amujw3_wp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:clearance-outline-bold" /></template>
<style>
.amujw3_wp {
  d: path("m9.5 13 2.5 2.5 2.5 -2.5");
}

.m0hvambgh {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pywr_yykw {
  d: path("m4 12 8 -8h8v8l-8 8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tl2fjsrpp {
  d: path("m9.5 9 2.5 2.5L14.5 9");
}

</style>
