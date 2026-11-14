<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2tm7bbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-drill-up" /></template>
<style>
.d2tm7bbyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 17h15.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 4.25 17M12 15v-4.5m-2.25 2.25L12 10.5l2.25 2.25M4.25 2.5H5.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 5.5 8H4.25A1.75 1.75 0 0 1 2.5 6.25v-2A1.75 1.75 0 0 1 4.25 2.5m7.25 0h1a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 12.5 8h-1a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 11.5 2.5m7 0h1.25a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 19.75 8H18.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 18.5 2.5");
}

</style>
