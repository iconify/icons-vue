<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_p8lxm1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-sensor" /></template>
<style>
.j_p8lxm1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 6h2.25a4.375 4.375 0 0 1 4.375 4.375v3.25A4.375 4.375 0 0 1 9.125 18h-2.25A4.375 4.375 0 0 1 2.5 13.625v-3.25A4.375 4.375 0 0 1 6.875 6M5.5 10.5h5m-5 3h5m5.75-4c1.5-1.5 3.25 1.5 5.25 0m-5.25 5c1.5-1.5 3.25 1.5 5.25 0");
}

</style>
