<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5htits8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-3d-print" /></template>
<style>
.a5htits8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h5a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2a2 2 0 0 1 2-2m1.75 5za.937.937 0 0 0 1.5 0a.625.625 0 0 0-.5-1h-.5a.625.625 0 0 0-.5 1m.75 5c-1.25-1-4.25-1.5-4.25 2c0 2 1 3 1.5 4.5l.5 2.25c.25.5 1 .5 1 0l.75-2.75c0-.5 1-.5 1 0l.75 2.75c0 .5.75.5 1 0l.5-2.25c.5-1.5 1.5-2.5 1.5-4.5c0-3.5-3-3-4.25-2m-3.75 3.25h7.5");
}

</style>
