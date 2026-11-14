<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh2jhcb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cursor-help" /></template>
<style>
.kh2jhcb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 3.5l11 4.5l-5 1.5l-2 5Zm12.25 12c0-1.1.95-1.75 2-1.75c1.15 0 2 .75 2 1.75c0 1.4-2 1.6-2 2.75m0 2.75h.01");
}

</style>
