<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4kvs6vdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floodplain" /></template>
<style>
.s4kvs6vdp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19m-19 5C6 15 9 15 12 17.5s6 2.5 9.5 0M17.819 5.935l.732 1.351A1.5 1.5 0 0 1 17.232 9.5h-1.464a1.5 1.5 0 0 1-1.319-2.214l.732-1.351a1.5 1.5 0 0 1 2.638 0M16.5 9.5v3");
}

</style>
