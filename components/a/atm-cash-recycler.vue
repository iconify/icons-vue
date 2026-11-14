<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="amu8asb5r"/><path class="vbquxeb3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-cash-recycler" /></template>
<style>
.amu8asb5r {
  d: path("M12.2 21.5H4v-19h16v8.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vbquxeb3r {
  d: path("M7 5h10v6H7Zm-.5 8.75h5.7m-5.45 3.5h.01m2.49 0h.01m2.49 0h.01m3.24-1h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

</style>
