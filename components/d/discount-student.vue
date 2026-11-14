<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="coqrexbmv"/><path class="fptai0b8y"/><path class="gmmm0ic3g"/><path class="pp2cmgbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discount-student" /></template>
<style>
.coqrexbmv {
  d: path("M11.25 2.75L19.75 7l-8.5 4.25L2.75 7Zm-4.5 6.5v3.25c1.257 1.257 4.449 1.611 6.796 1.062m2.204-2.091V9.25");
}

.fptai0b8y {
  d: path("M11.25 7H4.5v5.75");
}

.gmmm0ic3g {
  fill: currentColor;
  d: path("M3.75 12.75h1.5v2h-1.5Z");
}

.pp2cmgbmr {
  d: path("M16.5 14.25h5.25v7.5H16.5L13.75 18Zm.25 3.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
