<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="u1mon9cdo"/><path class="iwea3dacr"/><path class="nffgw9y5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:detect-ai-text-outline-bold" /></template>
<style>
.iwea3dacr {
  d: path("M12.5 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.nffgw9y5n {
  d: path("m19.5 19 2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u1mon9cdo {
  d: path("M3 15h9");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
