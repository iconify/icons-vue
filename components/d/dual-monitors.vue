<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slqfz4fkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dual-monitors" /></template>
<style>
.slqfz4fkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3.5h3a2.625 2.625 0 0 1 2.625 2.625v4.25A2.625 2.625 0 0 1 8.125 13h-3A2.625 2.625 0 0 1 2.5 10.375v-4.25A2.625 2.625 0 0 1 5.125 3.5m10.75 0h3A2.625 2.625 0 0 1 21.5 6.125v4.25A2.625 2.625 0 0 1 18.875 13h-3a2.625 2.625 0 0 1-2.625-2.625v-4.25A2.625 2.625 0 0 1 15.875 3.5M6.75 13v3h10.5v-3M12 16v4m-4 0h8");
}

</style>
