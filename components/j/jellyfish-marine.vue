<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq_77kjrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jellyfish-marine" /></template>
<style>
.nq_77kjrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 9.5a6.25 6.25 0 0 1 12.5 0c0 .75-.5 1.25-1.25 1.25H7c-.75 0-1.25-.5-1.25-1.25m2.75 3.25q-1 1.25 0 2.5t0 2.5m3.5-5q-1 1.25 0 2.5t0 2.5m3.5-5q-1 1.25 0 2.5t0 2.5m-12.75 3C4 20.75 4 20 5.25 20s1.25.75 2.5.75S9 20 10.25 20s1.25.75 2.5.75S14 20 15.25 20s1.25.75 2.5.75S19 20 20.25 20");
}

</style>
