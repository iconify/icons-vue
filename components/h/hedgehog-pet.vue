<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2igf3bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hedgehog-pet" /></template>
<style>
.z2igf3bts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.5 15L15 9l-.5-3.5l-2 2L11 4.25L9.25 7.5L6.5 5.75l-.25 3.5l-3.25 2l1.5 2.5l-1 3.75H17q3.75 0 4.5-2.5ZM7 17.5V20m8-2.5V20m1.25-6h.01");
}

</style>
