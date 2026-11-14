<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-8b-lijz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-supply-on" /></template>
<style>
.e-8b-lijz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 11h13.75a2.625 2.625 0 0 1 2.625 2.625v4.75A2.625 2.625 0 0 1 18.875 21H5.125A2.625 2.625 0 0 1 2.5 18.375v-4.75A2.625 2.625 0 0 1 5.125 11m3.625 0v10m6.5-10v10M7 8Q5.75 6.5 7 5.25T7 2.5M12 8q-1.25-1.5 0-2.75t0-2.75M17 8q-1.25-1.5 0-2.75t0-2.75");
}

</style>
