<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz_mf_y1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-network" /></template>
<style>
.vz_mf_y1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 12.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm.25-8.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-7.5 14a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm15 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM12 10.25v-3.5m-2 7.5l-3.75 3m7.75-3l3.75 3");
}

</style>
