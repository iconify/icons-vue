<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap44swkpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:license-plate-reader" /></template>
<style>
.ap44swkpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 12h13.75a2.625 2.625 0 0 1 2.625 2.625v3.75A2.625 2.625 0 0 1 18.875 21H5.125A2.625 2.625 0 0 1 2.5 18.375v-3.75A2.625 2.625 0 0 1 5.125 12M6 16.5h4m3 0h5m-8.75-14h5.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 7.5 4.75v-.5A1.75 1.75 0 0 1 9.25 2.5m.75 4a2 2 0 0 0 4 0");
}

</style>
