<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl123z_wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beaker-measure" /></template>
<style>
.wl123z_wr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5v6l-6 11c-.5 1 0 2 1.25 2h14.5c1.25 0 1.75-1 1.25-2l-6-11v-6M8 2.5h8M6 15h12M7.75 12H10m-5.25 6h2.5");
}

</style>
