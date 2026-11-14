<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5chu8nfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leak-detector" /></template>
<style>
.r5chu8nfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5h19M2.5 13h19M8.5 3h7v5.5h-7Zm2.5 7.75l1.5 1l-1 1.25m.5 3l1.5 1.75a2.25 2.25 0 1 1-3 0Z");
}

</style>
