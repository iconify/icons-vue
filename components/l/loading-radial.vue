<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxpsp_b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loading-radial" /></template>
<style>
.kxpsp_b6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v5m0 9v5M2.5 12h5m9 0h5m-6.25-3.25l3.5-3.5m-3.5 10l3.5 3.5m-10-3.5l-3.5 3.5m3.5-10l-3.5-3.5");
}

</style>
