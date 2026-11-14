<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6pg9cb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layout-dashboard" /></template>
<style>
.i6pg9cb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3zA2.25 2.25 0 0 1 7.5 5.25v13.5A2.25 2.25 0 0 1 5.25 21A2.25 2.25 0 0 1 3 18.75V5.25A2.25 2.25 0 0 1 5.25 3m7.875 0h5.25A2.625 2.625 0 0 1 21 5.625v2.75A2.625 2.625 0 0 1 18.375 11h-5.25A2.625 2.625 0 0 1 10.5 8.375v-2.75A2.625 2.625 0 0 1 13.125 3m-.75 11za1.875 1.875 0 0 1 1.875 1.875v3.25A1.875 1.875 0 0 1 12.375 21a1.875 1.875 0 0 1-1.875-1.875v-3.25A1.875 1.875 0 0 1 12.375 14m6.75 0zA1.875 1.875 0 0 1 21 15.875v3.25A1.875 1.875 0 0 1 19.125 21a1.875 1.875 0 0 1-1.875-1.875v-3.25A1.875 1.875 0 0 1 19.125 14");
}

</style>
