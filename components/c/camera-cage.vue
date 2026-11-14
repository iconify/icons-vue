<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hltbbtbdk"/><path class="nwm_msbil"/><path class="s5y31sbxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-cage" /></template>
<style>
.hltbbtbdk {
  d: path("M2.5 21.5V8A1.5 1.5 0 0 1 4 6.5h16A1.5 1.5 0 0 1 21.5 8v13.5m-13-15v-3h7v3");
}

.nwm_msbil {
  d: path("M5.5 9.5h13v9h-13Z");
}

.s5y31sbxh {
  d: path("M10.25 14a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
