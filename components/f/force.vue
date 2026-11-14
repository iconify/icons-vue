<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnnsa_bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:force" /></template>
<style>
.wnnsa_bnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 6h2a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 18h-2a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 16 6M2.5 12h7.25m-3-3l3 3l-3 3");
}

</style>
