<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqdspg-lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cartoning-machine" /></template>
<style>
.bqdspg-lx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 3.5l-3 5v11h9.669M16 12.431V8.5l-3-5m-10.5 5H16M15 15v6m0-3h6.5M19 15.5l2.5 2.5l-2.5 2.5");
}

</style>
