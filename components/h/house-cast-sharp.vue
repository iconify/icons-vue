<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kfnnw6bgb"/><path class="l27kgwbzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-cast-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kfnnw6bgb {
  d: path("M1 17L2 17C4.2091 17 6 18.7909 6 21L6 22M1 13L2 13C6.4183 13 10 16.5817 10 21L10 22M3.6709 9.4779L4.0568 9.1776L12 2.9963L22 10.7782L22.3859 11.0785M20 9.2218L20 21L14 21L13 21");
}

.l27kgwbzk {
  fill: currentColor;
  d: path("M3 21C3 21.5523 2.5523 22 2 22C1.4477 22 1 21.5523 1 21C1 20.4477 1.4477 20 2 20C2.5523 20 3 20.4477 3 21Z");
  stroke: none;
}

</style>
