<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmpcp4-1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flight-crew" /></template>
<style>
.mmpcp4-1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5c0-1.5 7.5-1.5 7.5 0L9.25 7.75h-5Zm10.5 0c0-1.5 7.5-1.5 7.5 0l-1.25 2.75h-5Zm-10 2.75H10m-5.75 0V10a2.5 2.5 0 0 0 5 0V7.75m4.75 0h6.5m-5.75 0V10a2.5 2.5 0 0 0 5 0V7.75M3 21c0-3.25 1.75-5.5 3.75-5.5s3.75 2.25 3.75 5.5m3 0c0-3.25 1.75-5.5 3.75-5.5S21 17.75 21 21");
}

</style>
