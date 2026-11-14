<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvsjsbc6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-pit-outdoor" /></template>
<style>
.zvsjsbc6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.5h18V21H3Zm9-14q4 3.5 3.5 6Q15 10 12 10T8.5 8.5Q8 6 12 2.5Zm-6 14L18 13M6 13l12 3.5");
}

</style>
