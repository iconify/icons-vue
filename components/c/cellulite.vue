<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_q3i4uga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cellulite" /></template>
<style>
.d_q3i4uga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5c-1.5 5.5-1 12 2.5 19m9.5-19c0 6.5-1.5 12.5-2.5 19M10 8.5h.01M13.5 11h.01m-3.01 3.5h.01");
}

</style>
