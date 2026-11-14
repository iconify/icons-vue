<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2-bewvph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cash-flow-financing" /></template>
<style>
.v2-bewvph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 5.75l3.587-2.192a1.75 1.75 0 0 1 1.826 0L16.5 5.75a1.484 1.484 0 0 1-.774 2.75H8.274A1.484 1.484 0 0 1 7.5 5.75m-1 5.5v6.25m5.5-6.25v6.25m5.5-6.25v1.4M3 20.5h9.7m8.3.5l-5.5-5.5m0 5v-5h5");
}

</style>
