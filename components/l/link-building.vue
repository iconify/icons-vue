<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwf0m2baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:link-building" /></template>
<style>
.gwf0m2baw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 12l-3 3a3.5 3.5 0 0 0 5 5l3-3m0-10l3-3a3.5 3.5 0 0 1 5 5l-3 3m-8.25 3.25l6.5-6.5M18 15v6m-3-3h6");
}

</style>
