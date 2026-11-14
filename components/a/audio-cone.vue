<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f08g_vwsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audio-cone" /></template>
<style>
.f08g_vwsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h5v6h-5Zm5 1.5L19 3M7.5 13.5L19 21m-5.221-10.682a6.5 6.5 0 0 1 0 3.364m4.658-5.236a11.5 11.5 0 0 1 0 7.108");
}

</style>
