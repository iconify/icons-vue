<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj617o30p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-booties" /></template>
<style>
.rj617o30p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h4.25v3H2.5Zm0 3v10c0 1.25.75 2 2 2H9c1 0 1.5-.75 1.5-1.5c0-1.75-1.25-3-3.25-3.25h-.5V7.5m6.75-3h4.25v3H13.5Zm0 3v10c0 1.25.75 2 2 2H20c1 0 1.5-.75 1.5-1.5c0-1.75-1.25-3-3.25-3.25h-.5V7.5");
}

</style>
