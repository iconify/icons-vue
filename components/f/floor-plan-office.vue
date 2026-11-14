<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dsjs6ccfs"/><path class="ibppi2bjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floor-plan-office" /></template>
<style>
.dsjs6ccfs {
  d: path("M9 21.5h12.5v-19h-19v19H5m4.5-19V10m-7 0H15m3 0h3.5");
}

.ibppi2bjd {
  d: path("M13 14h5v3.5h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
