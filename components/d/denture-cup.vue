<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eltqa97fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:denture-cup" /></template>
<style>
.eltqa97fk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 11l1 8.5A2 2 0 0 0 8 21h8a2 2 0 0 0 2-1.5l1-8.5M5.25 7.5h13.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 18.75 11H5.25A1.75 1.75 0 0 1 3.5 9.25A1.75 1.75 0 0 1 5.25 7.5m3.25-5c0 2.75 7 2.75 7 0");
}

</style>
