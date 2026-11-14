<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlr6j9bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breakfast-included" /></template>
<style>
.vlr6j9bhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.271 16.793Q11.652 17 11 17H7q-.197 0-.392-.019q-.196-.02-.388-.058q-.193-.038-.381-.095t-.37-.132t-.355-.168t-.336-.202t-.316-.234q-.151-.125-.29-.264t-.264-.29t-.234-.316q-.109-.163-.202-.336q-.092-.174-.168-.355q-.075-.182-.132-.37t-.095-.381t-.058-.388T3 13V8h12v5q0 .304-.046.605q-.046.3-.137.59t-.224.563q-.134.273-.307.523M15 9.5h1a2.25 2.25 0 0 1 0 4.5h-1M7 2.75V5m4-2.25V5m3.75 13l2 2L21 15.75");
}

</style>
