<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn7_bwbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ambulance-siren" /></template>
<style>
.pn7_bwbjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17v-5a5 5 0 0 1 10 0v5Zm-2 0h14v3.5H5Zm7-14.5v2M2.5 12h2m15 0h2m-17-7.5L6 6m13.5-1.5L18 6");
}

</style>
