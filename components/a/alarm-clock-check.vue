<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gavqc4b8l"/><path class="wry_o9rmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alarm-clock-check" /></template>
<style>
.gavqc4b8l {
  d: path("M4.5 13a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0ZM3 6l3-3m15 3l-3-3M6.5 18.5l-2 2m13-2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wry_o9rmj {
  d: path("m9 13.25l2 2l4-4");
}

</style>
