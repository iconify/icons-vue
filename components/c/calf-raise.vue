<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iixb5acyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calf-raise" /></template>
<style>
.iixb5acyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 2.5V13l3 6l4 2.5h3.5l-1-1.5l-3.5-2.5l-1-4.5V2.5m-8 18v-6m-2 2l2-2l2 2Z");
}

</style>
