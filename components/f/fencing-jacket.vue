<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8nx5ft1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fencing-jacket" /></template>
<style>
.a8nx5ft1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5h6v2.75l4.5 1.25L21 13l-2.5.5v8h-13v-8L3 13l1.5-6.5L9 5.25Zm0 2.75h6m-1 0L9 21.5");
}

</style>
