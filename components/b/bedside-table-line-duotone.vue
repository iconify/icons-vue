<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p65p1hbxh"/><path class="nym5net5m"/><path class="axy_-vb0r"/><path class="rho2h4_9z"/><path class="u3xw_g32v"/><path class="u-d3qccyr"/><path class="vy5waob-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bedside-table-line-duotone" /></template>
<style>
.axy_-vb0r {
  d: path("M2 14H22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nym5net5m {
  d: path("M10 20H14C17.7712 20 19.6569 20 20.8284 18.8284C22 17.6569 22 15.7712 22 12V10C22 6.22876 22 4.34315 20.8284 3.17157C19.6569 2 17.7712 2 14 2H10C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10V12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20Z");
}

.p65p1hbxh {
  d: path("M19 22V20.5M5 22V20.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rho2h4_9z {
  d: path("M2 8H22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.u-d3qccyr {
  stroke-linejoin: round;
  d: path("M12 11H12.0001");
}

.u3xw_g32v {
  stroke-linejoin: round;
  d: path("M12 5H12.0001");
}

.vy5waob-q {
  stroke-linejoin: round;
  d: path("M12 17H12.0001");
}

</style>
