<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epc08-bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exploded-view" /></template>
<style>
.epc08-bzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8V4.5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2V8Zm-1 8h17v3.5a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2Zm8.5-5.25v.5m0 1.5v.5");
}

</style>
