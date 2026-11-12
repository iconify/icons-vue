<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sc6p54bfo"/><path class="m5flx0poa"/><path class="l142rrhgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:brackets-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l142rrhgl {
  d: path("M9 21.9799C6.20875 21.916 4.5784 21.6494 3.46447 20.5355C2 19.071 2 16.714 2 11.9999C2 10.4203 2 9.10531 2.0551 7.99989");
}

.m5flx0poa {
  d: path("M3.46484 3.4644C4.57878 2.35047 6.20912 2.08384 9.00038 2.02002");
}

.sc6p54bfo {
  d: path("M15 2.02002C17.7913 2.08384 19.4216 2.35047 20.5355 3.4644C22 4.92887 22 7.28589 22 11.9999C22 16.714 22 19.071 20.5355 20.5355C19.4216 21.6494 17.7913 21.916 15 21.9799");
}

</style>
