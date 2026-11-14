<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bau7n2byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forex-prepaid-travel-card" /></template>
<style>
.bau7n2byr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.7 19H2.5V5h19v10.7m-19-6.2h19M6 14.5h3.5m8.5 0v7m-3.25-2.75L18 17l3.25 1.75M16.5 21.5l1.5-.75l1.5.75");
}

</style>
