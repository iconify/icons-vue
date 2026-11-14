<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1z5-t1mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drink-delivery" /></template>
<style>
.l1z5-t1mk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 7.5l1.5 14h8l.002-.02m.714-6.662L16.5 7.5M3.75 5h14.5v2.5H3.75ZM6.5 5l1.25-2.5h6.5L15.5 5m0 13.5h6m-2.75-2.75l2.75 2.75l-2.75 2.75");
}

</style>
