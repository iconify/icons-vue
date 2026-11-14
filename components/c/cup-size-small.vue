<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t73uqowda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cup-size-small" /></template>
<style>
.t73uqowda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h12v5a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4ZM15 5h1a2 2 0 0 1 0 4h-1m5.5 6.75c-.5-.75-1.25-1-2.25-1c-1.5 0-2.5.75-2.5 2c0 2.5 5.25 1.25 5.25 3.5C21 21.5 19.75 22 18.25 22C17 22 16 21.5 15.5 20.75");
}

</style>
