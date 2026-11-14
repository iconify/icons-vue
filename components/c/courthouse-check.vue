<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3qzoz4sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:courthouse-check" /></template>
<style>
.z3qzoz4sr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8L12 3l9.5 5Zm0 11.5h9.8m8.9 0h.3M6 11v5m4-5v5m4-5v3.8m4-3.8v3.8M14.75 18l2 2L21 15.75");
}

</style>
