<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ngio75bua"/><path class="azeni5ifw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-manhole" /></template>
<style>
.azeni5ifw {
  d: path("M10.25 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M13 12h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ngio75bua {
  d: path("M7.5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0m-5 5c2.5 0 2.5-5 5-5");
}

</style>
