<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ugdbidcqi"/><path class="l0zc9ibud"/><path class="q534om6ef"/><path class="c4khiwgvb"/><path class="tldtqlb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-config-outline-bold" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.l0zc9ibud {
  d: path("M8 10h8");
}

.q534om6ef {
  d: path("M14 8v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tldtqlb3m {
  d: path("M10 13v4");
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

</style>
