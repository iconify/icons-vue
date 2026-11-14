<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5g_25dvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:limestone" /></template>
<style>
.j5g_25dvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.322 14.033l2.409-7.225a1.75 1.75 0 0 1 1.071-1.095l5.525-1.973a1.75 1.75 0 0 1 1.322.059l5.031 2.322a1.75 1.75 0 0 1 .986 1.267l1.173 6.252a1.75 1.75 0 0 1-.43 1.505l-4.344 4.739a1.75 1.75 0 0 1-1.399.564l-6.453-.403a1.75 1.75 0 0 1-1.191-.576l-3.34-3.712a1.75 1.75 0 0 1-.36-1.724M9 9.5h.01M15.5 11h.01m-5.01 4.5h.01");
}

</style>
