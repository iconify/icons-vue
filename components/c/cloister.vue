<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hih6arkkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloister" /></template>
<style>
.hih6arkkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19M3 20V10a3 3 0 0 1 6 0v10m0-10a3 3 0 0 1 6 0v10m0-10a3 3 0 0 1 6 0v10M2.5 20h19");
}

</style>
