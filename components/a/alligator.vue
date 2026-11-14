<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br6zv3bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alligator" /></template>
<style>
.br6zv3bwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16v-5c0-2.5 1.5-4 4-4c1-1.5 3-1.5 4 0l10-2c1-.25 1.25 1.25.5 1.75l-1.75 1l-.75 2.5l-.75-1.5L10.5 13l4.25 1.75l.75-2l.75 2.75l4.75 2c.75.5.5 2-.5 1.75L5 19c-1.5 0-2.5-1.25-2.5-3Zm5.75-7h.01");
}

</style>
