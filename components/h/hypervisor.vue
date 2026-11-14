<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xan2a3bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hypervisor" /></template>
<style>
.xan2a3bex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9.5h12a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-5A3.5 3.5 0 0 1 6 9.5M6.25 3h3A1.75 1.75 0 0 1 11 4.75v3A1.75 1.75 0 0 1 9.25 9.5h-3A1.75 1.75 0 0 1 4.5 7.75v-3A1.75 1.75 0 0 1 6.25 3M2.5 13.5h19m-19 4h19");
}

</style>
