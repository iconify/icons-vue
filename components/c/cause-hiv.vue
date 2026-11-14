<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozsu0mr0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cause-hiv" /></template>
<style>
.ozsu0mr0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 20.5l8-10.5c1.5-2.5.75-6.75-2.5-6.75S8 7.5 9.5 10l.75 1M14 15.75l3.5 4.75");
}

</style>
