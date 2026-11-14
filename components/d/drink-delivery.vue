<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqud5fwwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drink-delivery" /></template>
<style>
.gqud5fwwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 7.5l1.5 14h8l.023-.219m.597-5.568L16.5 7.5M5 5h12a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 17 7.5H5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 5 5m1.5 0l1.25-2.5h6.5L15.5 5m0 13.5h6m-2.75-2.75l2.75 2.75l-2.75 2.75");
}

</style>
