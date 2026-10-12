<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rapca_b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eval-suite-sharp" /></template>
<style>
.rapca_b1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5L4.5 6.75l3-3m-4.75 7.5L4.5 13l3-3m-4.75 7.5l1.75 1.75l3-3m3.25-11h10.5m-10.5 6.25h10.5m-10.5 6.25h7");
}

</style>
