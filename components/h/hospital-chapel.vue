<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3ylkqbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hospital-chapel" /></template>
<style>
.c3ylkqbpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 11h7v10.5h-7ZM12 2.5c1.75 2 2.5 3.25 2.5 4.5c0 1.4-1.1 2.25-2.5 2.25S9.5 8.4 9.5 7c0-1.25.75-2.5 2.5-4.5Zm0 6.75V11M5 21.5h14");
}

</style>
