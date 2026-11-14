<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqsenradx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:background-remove" /></template>
<style>
.uqsenradx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6V2.5H6m12 0h3.5V6m0 12v3.5H18m-12 0H2.5V18M10 2.5h4m7.5 7.5v4M10 21.5h4M2.5 10v4M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2.5 9.5c0-2.25 2.5-3.75 5.5-3.75s5.5 1.5 5.5 3.75Z");
}

</style>
