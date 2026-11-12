<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pqx2-oyar"/><path class="tonplxqkt"/><path class="nmhvanepw"/><path class="pre11cbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-down-minimalistic-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmhvanepw {
  d: path("M20 11L3 11");
}

.pqx2-oyar {
  d: path("M10 16H3");
}

.pre11cbbs {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

.tonplxqkt {
  stroke-linejoin: round;
  d: path("M14 15L17.5 18L21 15");
}

</style>
