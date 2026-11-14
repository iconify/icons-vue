<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo0pm5b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:awareness-ribbon-check" /></template>
<style>
.mo0pm5b6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 21l7-9.5c1.75-2.5 1.5-9-2.5-9s-4.25 6.5-2.5 9l4.586 6.224m1.424 1.932L13.5 21m1.25-3l2 2L21 15.75");
}

</style>
