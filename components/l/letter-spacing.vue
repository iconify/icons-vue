<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb478mbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:letter-spacing" /></template>
<style>
.wb478mbah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 14.25l6-10.5l6 10.5M8.2 10.5h7.6M3.75 19h16.5m-14.5-2l-2 2l2 2m12.5-4l2 2l-2 2");
}

</style>
