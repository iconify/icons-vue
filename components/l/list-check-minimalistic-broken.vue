<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c6aatbbnu"/><path class="pqx2-oyar"/><path class="l4vllvb7o"/><path class="pre11cbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-check-minimalistic-broken" /></template>
<style>
.c6aatbbnu {
  d: path("M10 11L3 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4vllvb7o {
  stroke-linejoin: round;
  d: path("M14 13.5L16.1 16L20 11");
}

.pqx2-oyar {
  d: path("M10 16H3");
}

.pre11cbbs {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

</style>
