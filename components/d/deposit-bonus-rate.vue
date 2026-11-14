<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9p0npb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-bonus-rate" /></template>
<style>
.o9p0npb3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 20l12-14M4 7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM14 17a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm3.5-11c-1.5-3-4.5-3-4-.75c.25 1 2 1.25 4 .75m0 0c1.5-2.75 4.25-2.5 3.75-.5c-.25 1-1.75 1.25-3.75.5");
}

</style>
