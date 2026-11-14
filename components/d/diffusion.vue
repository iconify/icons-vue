<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d90mo6jwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diffusion" /></template>
<style>
.d90mo6jwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.5h.01m-.01 5h.01M6.5 12h.01m2.99 0h6m-2.25-2.25L15.5 12l-2.25 2.25M18.5 4.5h.01M21 12h.01m-2.51 7.5h.01");
}

</style>
