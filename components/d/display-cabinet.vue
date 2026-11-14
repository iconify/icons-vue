<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2xel8apk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:display-cabinet" /></template>
<style>
.k2xel8apk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v9a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 15V6A3.5 3.5 0 0 1 8 2.5m-.5 16v3m9-3v3m-12-11h15M8 8l2.5-2.5M8 16l2.5-2.5");
}

</style>
