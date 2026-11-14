<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp-46dggm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crew-rest-bunk" /></template>
<style>
.cp-46dggm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5v19m17-19v19M3.5 10h17m-17 7.5h17M8.5 6H9a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-.5a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 7.5H9a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-.5a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

</style>
