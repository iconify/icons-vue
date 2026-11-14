<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw6o4ibkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:instrument-case" /></template>
<style>
.zw6o4ibkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 8h10.25a4.375 4.375 0 0 1 4.375 4.375v1.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 14.125v-1.75A4.375 4.375 0 0 1 6.875 8M9.5 8V5.5h5V8m-12 4h19m-15-1.5v3m11-3v3");
}

</style>
