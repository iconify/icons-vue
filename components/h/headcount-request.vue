<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7diti5zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headcount-request" /></template>
<style>
.t7diti5zy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 21.5V18L2.5 15a1.25 1.25 0 0 1 2-1.5l.5.5V6.5a1.25 1.25 0 0 1 2.5 0V11V5A1.25 1.25 0 0 1 10 5v6v-4a1.25 1.25 0 0 1 2.5 0v9c0 1.75-1 2.75-2 3v2.5M18.75 4a1.375 1.375 0 0 1 2.75 0v9a1.25 1.25 0 0 1-1.25 1.25H16.5A1.25 1.25 0 0 1 15.25 13a1.25 1.25 0 0 1 1.25-1.25h2.25Zm-.5 10.25V17m-3 2l3-2l3 2m-6 2.75h.01m5.99 0h.01");
}

</style>
