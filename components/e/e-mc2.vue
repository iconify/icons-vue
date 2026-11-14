<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_974cc1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:e-mc2" /></template>
<style>
.v_974cc1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3.5l2 4.25l2.75-.5l-.5 2.75l4.25 2l-4.25 2l.5 2.75l-2.75-.5l-2 4.25l-2-4.25l-2.75.5l.5-2.75l-4.25-2l4.25-2l-.5-2.75l2.75.5Zm0 8.5h.01");
}

</style>
