<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as0n4pc2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:food-bank-box" /></template>
<style>
.as0n4pc2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 7.5L3 11v9.5h10.26M16 11.84V11l3.5-3M3 11h13M6.5 4.5a3 1.5 0 1 0 6 0a3 1.5 0 1 0-6 0Zm0 0V11m6-6.5V11M18 21.5l-3-3.25a2 2 0 1 1 3-2.5a2 2 0 1 1 3 2.5Z");
}

</style>
