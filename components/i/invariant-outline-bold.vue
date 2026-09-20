<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="duvzkqbwy"/><path class="m6r9k7-tj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invariant-outline-bold" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.duvzkqbwy {
  d: path("M8 9.5h8");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.m6r9k7-tj {
  d: path("M8 14.5h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
