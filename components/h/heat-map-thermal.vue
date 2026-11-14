<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs9vpgrcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-map-thermal" /></template>
<style>
.cs9vpgrcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7 18H3V3h15v5.2M8 3v15m5-15v14M3 8h15M3 13h10.9m-3.4-2.5h.01m6.24 6v-4.25a1.25 1.25 0 0 1 2.5 0v4.25a2.5 2.5 0 1 1-2.5 0Z");
}

</style>
