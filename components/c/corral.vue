<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn7v5ibba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corral" /></template>
<style>
.nn7v5ibba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10c4.5 3 14.5 3 19 0m-19 5c4.5 3 14.5 3 19 0M4 7.5V19m8-9.5V21m8-13.5V19");
}

</style>
