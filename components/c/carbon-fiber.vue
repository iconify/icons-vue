<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw4bs7bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-fiber" /></template>
<style>
.fw4bs7bra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h18v18H3Zm0 14l6.75-6.75m4.5-4.5L17 3M3 7l2.75 2.75m4.5 4.5L17 21M7 21l2.75-2.75m4.5-4.5L21 7M7 3l6.75 6.75m4.5 4.5L21 17");
}

</style>
