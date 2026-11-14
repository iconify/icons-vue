<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe2rnfvfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-blocked" /></template>
<style>
.qe2rnfvfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.484 12.533Q18.599 9.387 20.5 5q0-1.5-1.5-1.5h-3.5L14 8l2 1.5q-.339.903-.856 1.729m-4.049 3.88q-.747.467-1.595.891L8 14l-4.5 1.5V19q0 1.5 1.5 1.5q4.198-.233 7.853-3.622M3.5 3.5l17 17");
}

</style>
