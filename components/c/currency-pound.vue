<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0rx40bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:currency-pound" /></template>
<style>
.x0rx40bhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 7c-.5-1.75-1.75-2.5-3.25-2.5c-2 0-3.5 1.5-3.5 3.75V15c0 2-1 3.5-2.75 4.5h10M7 12h7");
}

</style>
