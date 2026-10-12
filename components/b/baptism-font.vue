<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc85d3bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baptism-font" /></template>
<style>
.hc85d3bgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c1.1 1.35 1.75 2.25 1.75 3.1a1.75 1.75 0 0 1-3.5 0c0-.85.65-1.75 1.75-3.1M3.6 10h16.8q.6 0 .27.5L18.33 14q-.33.5-.93.5H6.6q-.6 0-.93-.5l-2.34-3.5Q3 10 3.6 10m6.4 4.5v6.75m4-6.75v6.75m-7.25 0h10.5");
}

</style>
