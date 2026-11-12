<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v3bnzubkl"/><path class="s5xpay_7j"/><path class="tonplxqkt"/><path class="pre11cbbs"/><path class="qtz6yi5yq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-down-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pre11cbbs {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

.qtz6yi5yq {
  d: path("M20 10L9.5 10M5.25 10H3");
}

.s5xpay_7j {
  d: path("M10 18H3");
}

.tonplxqkt {
  stroke-linejoin: round;
  d: path("M14 15L17.5 18L21 15");
}

.v3bnzubkl {
  d: path("M10 14H3");
}

</style>
