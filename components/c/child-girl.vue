<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="birg5y8_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:child-girl" /></template>
<style>
.birg5y8_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 10.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m2.653-5.505l-.721-1.154a.76.76 0 0 0-1.307.034a1.2 1.2 0 0 0 .541 1.669l.709.331a.612.612 0 0 0 .778-.88m2.194 0l.721-1.154a.76.76 0 0 1 1.307.034a1.2 1.2 0 0 1-.541 1.669l-.709.331a.612.612 0 0 1-.778-.88M4.5 21.5C4.5 19 7.75 17 12 17s7.5 2 7.5 4.5");
}

</style>
