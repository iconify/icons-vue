<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1tnhxlgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:breakfast-included" /></template>
<style>
.t1tnhxlgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.979 16.878Q11.497 17 11 17H7q-.197 0-.392-.019q-.196-.02-.388-.058q-.193-.038-.381-.095t-.37-.132t-.355-.168t-.336-.202t-.316-.234q-.151-.125-.29-.264t-.264-.29t-.234-.316q-.109-.163-.202-.336q-.092-.174-.168-.355q-.075-.182-.132-.37t-.095-.381t-.058-.388T3 13V8h12v5q0 .588-.169 1.151M15 9.5h1a2.25 2.25 0 0 1 0 4.5h-1M7 2.75V5m4-2.25V5m3.75 13l2 2L21 15.75");
}

</style>
