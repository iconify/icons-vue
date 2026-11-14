<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9guaccnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:etl" /></template>
<style>
.t9guaccnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5H3v8h3.5M3 7.5h3m2.5-4H14m-2.75 0v8m5.25-8v8h4M3 17.5h17.5m-3-3l3 3l-3 3");
}

</style>
