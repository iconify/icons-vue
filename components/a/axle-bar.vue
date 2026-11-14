<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chrx80c8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:axle-bar" /></template>
<style>
.chrx80c8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6zA1.75 1.75 0 0 1 6 7.75v8.5A1.75 1.75 0 0 1 4.25 18a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 4.25 6m15.5 0za1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 19.75 18A1.75 1.75 0 0 1 18 16.25v-8.5A1.75 1.75 0 0 1 19.75 6M6 12h2.75m6.5 0H18m-7.5-2h3a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 13.5 14h-3a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 10.5 10");
}

</style>
