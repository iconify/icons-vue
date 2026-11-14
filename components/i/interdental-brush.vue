<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-qcnubto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interdental-brush" /></template>
<style>
.a-qcnubto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5c0-2.5 2-3 2.75-1.5C6 7.5 8 8 8 10.5c0 3.5-1 6.5-1.5 9q-1.25 2-2.5 0c-.5-2.5-1.5-5.5-1.5-9m13.5 0c0-2.5 2-3 2.75-1.5c.75-1.5 2.75-1 2.75 1.5c0 3.5-1 6.5-1.5 9q-1.25 2-2.5 0C17 17 16 14 16 10.5m-4-8v15M10.5 10h3m-3 2.75h3M11 15.5h2");
}

</style>
