<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp8h5kg6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai" /></template>
<style>
.rp8h5kg6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5Q9.5 14 17 14q-7.5 0-7.5 7.5Q9.5 14 2 14q7.5 0 7.5-7.5Zm9-4.25q0 2.25 2.25 2.25q-2.25 0-2.25 2.25q0-2.25-2.25-2.25q2.25 0 2.25-2.25ZM20 9.5c0 1.25.75 2 2 2c-1.25 0-2 .75-2 2c0-1.25-.75-2-2-2c1.25 0 2-.75 2-2Z");
}

</style>
