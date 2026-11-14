<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si-iwbb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:landing-gear" /></template>
<style>
.si-iwbb4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19V5a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3ZM12 8v9.5m-4 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0M7.5 8l4.5 4");
}

</style>
