<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbj2krbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-water-syringe" /></template>
<style>
.wbj2krbsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 3.5l8 8l-3 3l-8-8ZM13 13l3 3M2.5 7.5l5-5M5 5L3 3m17 13h.01M19 19h.01M16 20h.01");
}

</style>
