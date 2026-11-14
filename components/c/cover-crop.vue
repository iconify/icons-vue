<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ds7mqza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cover-crop" /></template>
<style>
.y0ds7mqza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.25h19v4.5h-19Zm2 0v-4m0 0q-2.25 0-2.25-3m2.25 3q2.25 0 2.25-3m5.25 7v-4m0 0q-2.25 0-2.25-3m2.25 3q2.25 0 2.25-3m5.25 7v-4m0 0q-2.25 0-2.25-3m2.25 3q2.25 0 2.25-3");
}

</style>
