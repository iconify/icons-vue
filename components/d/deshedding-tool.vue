<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es3-hlbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deshedding-tool" /></template>
<style>
.es3-hlbcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 12.75v-7.5a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v7.5m-9 0h13a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-13a2.5 2.5 0 0 1-2.5-2.5a2.5 2.5 0 0 1 2.5-2.5m-1 5l1.5 3l1.5-3l1.5 3l1.5-3l1.5 3l1.5-3l1.5 3l1.5-3l1.5 3l1.5-3");
}

</style>
