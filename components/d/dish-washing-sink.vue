<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7l5_cpva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dish-washing-sink" /></template>
<style>
.l7l5_cpva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13h18v3.5a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm3 0V6a3.5 3.5 0 0 1 7 0v1m-1.5 3h.01m2.99 0h.01");
}

</style>
