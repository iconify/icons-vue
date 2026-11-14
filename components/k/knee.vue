<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0pbvs9wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:knee" /></template>
<style>
.m0pbvs9wk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5v6c-1.5 1-1.25 3 .75 3.25H13c1.75-.25 2-2.25.5-3.25v-6m-5 19V16c-1.5-1-1.25-2 .25-2H13c1.5 0 1.75 1 .25 2v5.5M16 12.75a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0Z");
}

</style>
