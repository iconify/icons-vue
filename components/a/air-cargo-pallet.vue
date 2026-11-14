<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xndmjbrly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-cargo-pallet" /></template>
<style>
.xndmjbrly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h10.5v9.25H3Zm10.5 17h0h-2v-2.5H9V20H7v-2.5H4.5V20h-2v-5h11v2.1M8.25 3v9.25M19 14v7.75m-3-3l3-2.25l3 2.25m-4.5 3h3");
}

</style>
