<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq1mbykcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-waffle" /></template>
<style>
.pq1mbykcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3.5h.5A1.75 1.75 0 0 1 7.5 5.25v.5A1.75 1.75 0 0 1 5.75 7.5h-.5A1.75 1.75 0 0 1 3.5 5.75v-.5A1.75 1.75 0 0 1 5.25 3.5m6.5 0h.5A1.75 1.75 0 0 1 14 5.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 5.75v-.5a1.75 1.75 0 0 1 1.75-1.75m6.5 0h.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-13 6.5h.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 5.75 14h-.5a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 5.25 10m6.5 0h.5A1.75 1.75 0 0 1 14 11.75v.5A1.75 1.75 0 0 1 12.25 14h-.5A1.75 1.75 0 0 1 10 12.25v-.5A1.75 1.75 0 0 1 11.75 10m6.5 0h.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 18.75 14h-.5a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 18.25 10m-13 6.5h.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75m6.5 0h.5A1.75 1.75 0 0 1 14 18.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 18.75v-.5a1.75 1.75 0 0 1 1.75-1.75m6.5 0h.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
