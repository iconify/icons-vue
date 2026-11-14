<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p61z5u_ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:headphones-noise-cancelling" /></template>
<style>
.p61z5u_ij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13v-1.5a7.75 7.75 0 0 1 15.5 0V13M4.375 13za1.875 1.875 0 0 1 1.875 1.875v3.75A1.875 1.875 0 0 1 4.375 20.5A1.875 1.875 0 0 1 2.5 18.625v-3.75A1.875 1.875 0 0 1 4.375 13m15.25 0za1.875 1.875 0 0 1 1.875 1.875v3.75a1.875 1.875 0 0 1-1.875 1.875a1.875 1.875 0 0 1-1.875-1.875v-3.75A1.875 1.875 0 0 1 19.625 13M9 17q1.5-2.5 3 0t3 0m-5.5 3l5-6");
}

</style>
