<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_v0enb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:back-to-school-sale" /></template>
<style>
.w_v0enb1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.683 15.067L8 19.75L2.5 21.5L4.25 16L16.5 3.75l3.75 3.75l-5.233 5.233M4.25 16L8 19.75m6-13.5L17.75 10m-3 11.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
