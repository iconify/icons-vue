<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbhn0-bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hoarfrost" /></template>
<style>
.rbhn0-bch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 19.5l15-15m-11 11L6.5 8m5.5 3l7.5 1M18 15v6m-2.5-4.5l5 3m-5 0l5-3");
}

</style>
