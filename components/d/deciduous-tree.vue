<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz70hrm2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deciduous-tree" /></template>
<style>
.qz70hrm2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.61 6.5a4.5 4.5 0 0 1 8.78 0a4.25 4.25 0 0 1 1.34 8.32A3.25 3.25 0 0 1 12 16.58a3.25 3.25 0 0 1-5.73-1.76A4.25 4.25 0 0 1 7.61 6.5M12 17.75v3.5m-2.5 0h5");
}

</style>
