<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uso_4tooj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-combo" /></template>
<style>
.uso_4tooj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 14h1A1.75 1.75 0 0 1 7 15.75v4a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 4.25 14m7.25-2.5h1a1.75 1.75 0 0 1 1.75 1.75v6.5a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-6.5a1.75 1.75 0 0 1 1.75-1.75m7.25-2h1a1.75 1.75 0 0 1 1.75 1.75v8.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 17 19.75v-8.5a1.75 1.75 0 0 1 1.75-1.75m-16.25 1L9 6l5.25 2l7.25-5.5m-19 8h.01m18.99-8h.01");
}

</style>
