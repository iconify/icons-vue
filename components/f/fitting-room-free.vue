<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao9qe1_iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fitting-room-free" /></template>
<style>
.ao9qe1_iv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19M4 3v17c1.5 1 3-.5 4.5.5s3-1 4.5 0q.078.051.157.093M20 13.135V3M9 5.5V17m5.5-11.5v9.7m0 2.8l2.5 2.5l4.5-5");
}

</style>
