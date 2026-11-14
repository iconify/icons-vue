<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg0fwf4lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kefir" /></template>
<style>
.cg0fwf4lj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.5h10a2 2 0 0 0 2-2v-8c0-2-4-2-4-4V7H9v.5c0 2-4 2-4 4v8a2 2 0 0 0 2 2Zm1.5-18h7V7h-7ZM5 13.5h14");
}

</style>
