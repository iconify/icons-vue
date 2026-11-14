<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu1tjwbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-supply-on" /></template>
<style>
.tu1tjwbrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19v10h-19Zm6.25 0v10m6.5-10v10M7 8Q5.75 6.5 7 5.25T7 2.5M12 8q-1.25-1.5 0-2.75t0-2.75M17 8q-1.25-1.5 0-2.75t0-2.75");
}

</style>
