<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3gutx_lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:engine-telegraph" /></template>
<style>
.x3gutx_lj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm7 7V21m-4 0h8M12 9.5l3-3m-3 3h.01");
}

</style>
