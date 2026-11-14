<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na6dt4b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cycle-three" /></template>
<style>
.na6dt4b6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.5 4.75l5.75 10M20 12l-.75 2.75L16.5 14m1.5 3.5H6m2.75-2.75L6 17.5l2.75 2.75m-4-5.5l6-10.5M8 5l2.75-.75L11.5 7");
}

</style>
