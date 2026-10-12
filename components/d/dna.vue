<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czvk_qbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dna" /></template>
<style>
.czvk_qbei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75C7 7.25 17 7.5 17 12S7 16.75 7 21.25m10-18.5C17 7.25 7 7.5 7 12s10 4.75 10 9.25M9.75 4.5h4.5m-5 7.5h5.5m-5 7.5h4.5");
}

</style>
