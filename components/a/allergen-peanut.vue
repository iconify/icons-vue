<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prcgqp-2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:allergen-peanut" /></template>
<style>
.prcgqp-2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10.5c-2-2-1-8 3.5-8s5.5 6 3.5 8c2.5 2 2 9.5-3.5 9.5s-6-7.5-3.5-9.5m12 4V18m0 3h.01");
}

</style>
