<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv_atwbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-seats" /></template>
<style>
.bv_atwbpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14V8a2 2 0 0 1 2-2H7a2 2 0 0 1 2 2v6m0 0V8a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v6m0 0V8a2 2 0 0 1 2-2h1.5a2 2 0 0 1 2 2v6M4 14h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 17H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 14m.5 3v3.5m15-3.5v3.5");
}

</style>
