<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot7z-enmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:double-end-bag" /></template>
<style>
.ot7z-enmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h10m-5 0v3m0 0C15.5 8 16.5 10 16.5 12a4.5 4.5 0 0 1-9 0c0-2 1-4 4.5-6.5m0 11v5m-5 0h10");
}

</style>
