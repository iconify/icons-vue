<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mir03abqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bookcase" /></template>
<style>
.mir03abqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.75h18m-16.25 0v18.5m14.5-18.5v18.5M4.75 8.75h14.5m-14.5 6h14.5m-14.5 5h14.5M7.5 7.25v-2.5m2.25 2.5v-3m2.25 3v-2m2.25 2l1.5-2.5m-3.25 8.5V10.5m2.25 2.75v-3m2.25 3V11m-9.5 7.25v-2m2.25 2v-2.5m2.25 2.5V16.5");
}

</style>
