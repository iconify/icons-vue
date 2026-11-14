<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw4sph8zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:geothermal-vent" /></template>
<style>
.uw4sph8zl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h19m-16 0l4-4.5h5l4 4.5M8.5 13c-2-2.5 2-5.5 0-8.5m3.5 8c-2-3 2-6 0-9.5m3.5 10c-2-2.5 2-5.5 0-8.5");
}

</style>
