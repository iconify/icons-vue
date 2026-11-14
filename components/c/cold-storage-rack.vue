<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgo-zto3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cold-storage-rack" /></template>
<style>
.pgo-zto3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5v19m17-19v11.3m-17-4.3h17M3.5 17h8.9M8.25 4h2.5a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 6.5 7.75v-2A1.75 1.75 0 0 1 8.25 4m0 8.25h1.5A1.75 1.75 0 0 1 11.5 14v1.25A1.75 1.75 0 0 1 9.75 17h-1.5a1.75 1.75 0 0 1-1.75-1.75V14a1.75 1.75 0 0 1 1.75-1.75M18 15v6.5m2.815-4.875l-5.63 3.25m0-3.25l5.63 3.25");
}

</style>
