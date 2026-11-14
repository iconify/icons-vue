<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q7bqzrbwd"/><path class="szkih0b1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floating-roof-tank" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7bqzrbwd {
  d: path("M4 3.5v15a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-15M4 13h16");
}

.szkih0b1u {
  d: path("M8.375 10.25h7.25A1.375 1.375 0 0 1 17 11.625A1.375 1.375 0 0 1 15.625 13h-7.25A1.375 1.375 0 0 1 7 11.625a1.375 1.375 0 0 1 1.375-1.375");
}

</style>
