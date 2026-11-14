<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt2lgonlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-hospital-cover" /></template>
<style>
.mt2lgonlo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6v13m0-4h18M3 15h18v4M5.5 10h5v3.25h-5Zm7.5 5v-2.75a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2V15");
}

</style>
