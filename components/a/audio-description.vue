<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mau00xb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audio-description" /></template>
<style>
.mau00xb0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17.75L6 6.75l3.25 11M4 14h4m3.25-7.25v11h1.5a5.5 5.5 0 0 0 0-11Zm8.5 1.5q1.5 1.5 1.5 3.75c0 2.25-.5 2.75-1.5 3.75");
}

</style>
