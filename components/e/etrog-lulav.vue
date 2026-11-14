<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl9lb2bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:etrog-lulav" /></template>
<style>
.jl9lb2bou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5v19m-3-17L7 14l3-9.5M11.5 16a4.5 5 0 1 0 9 0a4.5 5 0 1 0-9 0m-6 1.5h3M16 11V8.75m0 1c1-1.75 2.5-2.25 4-2c-.5 1.5-2 2.25-4 2");
}

</style>
