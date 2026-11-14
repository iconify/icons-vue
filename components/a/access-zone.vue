<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlbwxsb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:access-zone" /></template>
<style>
.vlbwxsb6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.75V7a2.5 2.5 0 0 1 2.5-2.5h2m9 0h2A2.5 2.5 0 0 1 21 7v.75m0 8.5V17a2.5 2.5 0 0 1-2.5 2.5h-2m-9 0h-2A2.5 2.5 0 0 1 3 17v-.75M10.25 4.5h3.5m7.25 6v3m-7.25 6h-3.5M3 13.5v-3m9 1.5h.01");
}

</style>
