<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfty_1m3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:family-four" /></template>
<style>
.bfty_1m3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm13 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM2.5 18v-4.75c0-1.75 1.25-2.75 3-2.75m13 0c1.75 0 3 1 3 2.75V18M7 13.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm6.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM5.5 21c0-1.75 1.4-2.75 3.25-2.75S12 19.25 12 21m0 0c0-1.75 1.4-2.75 3.25-2.75s3.25 1 3.25 2.75");
}

</style>
