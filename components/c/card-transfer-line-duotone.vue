<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h9njkdbfq"/><path class="l6htmv4au"/><path class="aq84iuhhy"/><path class="vqfns1bta"/><path class="j-a1kqp-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-transfer-line-duotone" /></template>
<style>
.aq84iuhhy {
  stroke-linejoin: round;
  d: path("M15.5 14V20M13.5 18L15.5 20L17.5 18");
}

.h9njkdbfq {
  d: path("M21.9991 11C21.99 7.8857 21.8915 6.23467 20.8284 5.17157C19.6569 4 17.7712 4 14 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H11.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-a1kqp-o {
  d: path("M2 10L22 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.l6htmv4au {
  stroke-linejoin: round;
  d: path("M20 20V14M18 16L20 14L22 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vqfns1bta {
  d: path("M10 16H6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
