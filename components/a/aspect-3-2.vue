<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue-3q-bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aspect-3-2" /></template>
<style>
.ue-3q-bej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.75h6.75a1.5 1.5 0 0 1 1.5 1.5v3.5a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5v-3.5A1.5 1.5 0 0 1 4 8.75m12.5-1.5H20a1.5 1.5 0 0 1 1.5 1.5v6.75A1.5 1.5 0 0 1 20 17h-3.5a1.5 1.5 0 0 1-1.5-1.5V8.75a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
