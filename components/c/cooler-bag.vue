<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da_rmobhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cooler-bag" /></template>
<style>
.da_rmobhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5h10a3.5 3.5 0 0 1 3.5 3.5v6.5A3.5 3.5 0 0 1 17 21H7a3.5 3.5 0 0 1-3.5-3.5V11A3.5 3.5 0 0 1 7 7.5m-3.5 3h17M8 7.5v-2A1.5 1.5 0 0 1 9.5 4h5A1.5 1.5 0 0 1 16 5.5v2m-4 6V18m1.949-3.375l-3.898 2.25m3.898 0l-3.898-2.25");
}

</style>
