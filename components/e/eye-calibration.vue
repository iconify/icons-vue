<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhxdp_e-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-calibration" /></template>
<style>
.fhxdp_e-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12C8 9.5 9.75 8.25 12 8.25S16 9.5 17.5 12c-1.5 2.5-3.25 3.75-5.5 3.75S8 14.5 6.5 12Zm5.5 0h.01M4.5 4.5h.01m14.99 0h.01M4.5 19.5h.01m14.99 0h.01");
}

</style>
