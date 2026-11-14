<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="reqdedbeg"/><path class="vtev_eblf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dump-bin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.reqdedbeg {
  d: path("M4.657 12h14.686a1.75 1.75 0 0 1 1.713 2.111l-1.263 6A1.75 1.75 0 0 1 18.08 21.5H5.92a1.75 1.75 0 0 1-1.713-1.389l-1.263-6A1.75 1.75 0 0 1 4.657 12M8 12l.5 9.5M12 12v9.5m4-9.5l-.5 9.5M3.25 16.75h17.5");
}

.vtev_eblf {
  d: path("M5 7.5h1.5A1.5 1.5 0 0 1 8 9v1.5A1.5 1.5 0 0 1 6.5 12H5a1.5 1.5 0 0 1-1.5-1.5V9A1.5 1.5 0 0 1 5 7.5m3.5 1.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M17 6.5h.5A1.5 1.5 0 0 1 19 8v2.5a1.5 1.5 0 0 1-1.5 1.5H17a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 17 6.5");
}

</style>
