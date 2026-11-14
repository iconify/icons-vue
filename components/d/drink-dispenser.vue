<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z87tepnyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drink-dispenser" /></template>
<style>
.z87tepnyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 6h11v10a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2Zm1 0V4.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V6m1 7.5h3.5V16m-12.5 2l-1 3h9l-1-3");
}

</style>
