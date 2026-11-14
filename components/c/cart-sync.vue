<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ev845ddob"/><path class="z5dhh8blc"/><path class="v-kojjb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-sync" /></template>
<style>
.ev845ddob {
  d: path("M2.5 3h2l2.75 9.75h7.57m2.151-.737L19 5.25H5.25m0 12.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m4.25 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.5-.75a3.25 3.25 0 0 1 6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-kojjb-r {
  d: path("m14.25 21l.75-1.75l1.75.75");
}

.z5dhh8blc {
  d: path("M21.75 15L21 16.75L19.25 16M21 19.25a3.25 3.25 0 0 1-6 0");
}

</style>
