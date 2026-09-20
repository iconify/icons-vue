<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c0j1whzwq"/><path class="pdahcqbfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:frying-pan-outline-regular" /></template>
<style>
.c0j1whzwq {
  d: path("M3 11h12c0 5 -3 8 -6 8s-6 -3 -6 -8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pdahcqbfu {
  d: path("m15 11 6 -6");
}

</style>
