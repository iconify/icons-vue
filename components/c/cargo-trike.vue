<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af7sllb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cargo-trike" /></template>
<style>
.af7sllb8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 5.5h10.5v8H11Zm-8.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8.5 1.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.75 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5 16.5l6-4m-3 2l-1.5-6M5 8.5h3.5m4-3l-1-2.5H14");
}

</style>
