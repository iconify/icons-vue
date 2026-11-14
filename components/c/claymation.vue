<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6jzo-bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claymation" /></template>
<style>
.n6jzo-bdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm3.75 6.5c2.5 0 4.25 1.25 5 2.75l2.5-.5c1.5-.25 2.25 1.75.75 2.5l-2.75 1c0 2.25-2 3-5.5 3s-5.5-.75-5.5-3l-2.75-1c-1.5-.75-.75-2.75.75-2.5l2.5.5c.75-1.5 2.5-2.75 5-2.75Z");
}

</style>
