<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy64ga9dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:archive-shelf" /></template>
<style>
.vy64ga9dx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h19m-18 0V7h5.75V4.5h5.5V7h5.75v13.5M9.25 7v13.5M14.75 7v13.5M5.25 11H7.5m3.25-2h2.5m3.25 2h2.25");
}

</style>
