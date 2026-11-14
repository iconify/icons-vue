<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz_skeycz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-scaler" /></template>
<style>
.oz_skeycz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 18l6.5-6.5l3 3L6 21Zm8-5l3.5-3.5m0 0c0-4 2.5-6.5 5.25-6.5c1.75 0 1.75 2.5-.25 4.25");
}

</style>
