<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar-76wveb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lens-adapter" /></template>
<style>
.ar-76wveb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4a1 1 0 0 1 1-1h1.5a1 1 0 0 1 1 1v3.5h11v-1a1 1 0 0 1 1-1H20a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1h-1.5a1 1 0 0 1-1-1v-1h-11V20a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm9 3.5v9");
}

</style>
