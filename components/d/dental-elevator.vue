<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9u6ytbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-elevator" /></template>
<style>
.g9u6ytbrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.768 12.757l2.475 2.475l-6.011 6.011l-2.475-2.475ZM10 14l4.5-4.5m0 0c1-3 3-6 6-6.75c.5 3-2.5 5.75-6 6.75Z");
}

</style>
