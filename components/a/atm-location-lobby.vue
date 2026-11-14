<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iifyc9bkn"/><path class="oha595e2x"/><path class="k_ybatboe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-location-lobby" /></template>
<style>
.iifyc9bkn {
  d: path("M3.5 21.5v-12l8.5-6l8.5 6v12");
}

.k_ybatboe {
  d: path("M9.25 13.75h5.5v3.5h-5.5Z");
}

.oha595e2x {
  d: path("M6.5 11h11v10.5h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
