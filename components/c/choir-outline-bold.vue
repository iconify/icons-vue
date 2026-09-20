<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lo7kp72nh"/><path class="pemn838wn"/><path class="pb1wrt76j"/><path class="nnidkxr0z"/><path class="zzl1n0_hp"/><path class="k2lsbgbpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:choir-outline-bold" /></template>
<style>
.k2lsbgbpx {
  d: path("M14 17a4 4 0 0 1 8 0");
}

.lo7kp72nh {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nnidkxr0z {
  d: path("M2 17a4 4 0 0 1 8 0");
}

.pb1wrt76j {
  d: path("M15 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zzl1n0_hp {
  d: path("M8 15a4 4 0 0 1 8 0");
}

</style>
