<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="khhypgwbg"/><path class="ij9zn-b0e"/><path class="d8ir8h8wj"/><path class="l13ee7boy"/><path class="so03mlora"/><path class="l-qc8om1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bedside-table-4-broken" /></template>
<style>
.d8ir8h8wj {
  d: path("M15 12V15");
}

.ij9zn-b0e {
  d: path("M12 20V8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.khhypgwbg {
  d: path("M19 22V20.5M5 22V20.5");
}

.l-qc8om1x {
  d: path("M2 8H5M9 8H22");
}

.l13ee7boy {
  d: path("M9 12V15");
}

.so03mlora {
  d: path("M12 2H10C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10V12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H14C17.7712 20 19.6569 20 20.8284 18.8284C22 17.6569 22 15.7712 22 12V10C22 6.22876 22 4.34315 20.8284 3.17157C19.8853 2.22849 18.4796 2.04456 16 2.00869");
}

</style>
