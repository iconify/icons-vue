<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bow7yubgw"/><path class="tq61_obnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-plus-sharp-fill" /></template>
<style>
.bow7yubgw {
  fill: currentColor;
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 10C23 10.5523 22.5523 11 22 11L13 11L13 20C13 20.5523 12.5523 21 12 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3ZM3 8L3 10L21 10L21 8L3 8Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tq61_obnf {
  d: path("M19 14V20M16 17H22");
}

</style>
