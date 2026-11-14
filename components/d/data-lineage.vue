<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzrk9eh8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-lineage" /></template>
<style>
.pzrk9eh8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.5zA2.5 2.5 0 0 1 7.5 12A2.5 2.5 0 0 1 5 14.5A2.5 2.5 0 0 1 2.5 12A2.5 2.5 0 0 1 5 9.5m14-6zA2.5 2.5 0 0 1 21.5 6A2.5 2.5 0 0 1 19 8.5A2.5 2.5 0 0 1 16.5 6A2.5 2.5 0 0 1 19 3.5m0 12za2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5a2.5 2.5 0 0 1 2.5-2.5M7.5 12H12V6h4.5M12 12v6h4.5");
}

</style>
