<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpsgy_08q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:evapotranspiration" /></template>
<style>
.dpsgy_08q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 20.5h14m-7 0V13m0 3c0-3-2-4.5-5.5-4.5c0 3 2 4.5 5.5 4.5m0-1.5c0-2.5 2-4 5.5-4c0 3-2 4-5.5 4m-4.5-7q-1-1.25 0-2.5t0-2.5m4.5 5Q11 6.25 12 5t0-2.5m4.5 5q-1-1.25 0-2.5t0-2.5");
}

</style>
