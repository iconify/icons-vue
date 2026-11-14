<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfiw824it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-driver" /></template>
<style>
.cfiw824it {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.5v2a3 3 0 0 0 6 0v-2M5 6.5c0-2.75 2-4.25 4.5-4.25S14 3.75 14 6.5m-9 0h12m-5.564 14H2.5c0-3.25 3-5.5 7-5.5a9.7 9.7 0 0 1 2.249.256m4.001-.006h4.5a1.5 1.5 0 0 1 1.5 1.5v3.5a1.5 1.5 0 0 1-1.5 1.5h-4.5a1.5 1.5 0 0 1-1.5-1.5v-3.5a1.5 1.5 0 0 1 1.5-1.5m2.25 0V18");
}

</style>
