<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smnt7g4qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bin-location" /></template>
<style>
.smnt7g4qa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5V4m19 0v17.5M2.5 11h19m-19 8h19M7.5 6.5h1a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 8.5 11h-1a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 7.5 6.5m8 0h1a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 16.5 11h-1a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 15.5 6.5M9.75 14h4.5A1.75 1.75 0 0 1 16 15.75v1.5A1.75 1.75 0 0 1 14.25 19h-4.5A1.75 1.75 0 0 1 8 17.25v-1.5A1.75 1.75 0 0 1 9.75 14M12 16.5h.01");
}

</style>
