<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxq5i0h0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:comb-pick" /></template>
<style>
.kxq5i0h0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 14h9.5a3.75 3.75 0 0 1 3.75 3.75a3.75 3.75 0 0 1-3.75 3.75h-9.5a3.75 3.75 0 0 1-3.75-3.75A3.75 3.75 0 0 1 7.25 14M7 2.5V14m3.5-11.5V14M14 2.5V14m3.5-11.5V14");
}

</style>
