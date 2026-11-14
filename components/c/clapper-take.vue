<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_r-kybti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clapper-take" /></template>
<style>
.t_r-kybti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18v8.5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2ZM1.974 8.181l15.975-5.814l1.026 2.819L3 11Zm7.987-2.907l-.383 3.332m5.082-5.042l-.384 3.332");
}

</style>
