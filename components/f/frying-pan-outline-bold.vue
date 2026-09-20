<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c0j1whzwq"/><path class="pdahcqbfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:frying-pan-outline-bold" /></template>
<style>
.c0j1whzwq {
  d: path("M3 11h12c0 5 -3 8 -6 8s-6 -3 -6 -8");
}

.pdahcqbfu {
  d: path("m15 11 6 -6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
