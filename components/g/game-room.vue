<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f06acy5hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:game-room" /></template>
<style>
.f06acy5hv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8h10a5 5 0 0 1 4 7c0 2-1.25 3-2.75 3c-1.25 0-2-.75-2.75-1.5h-7C7.75 17.25 7 18 5.75 18C4.25 18 3 17 3 15a5 5 0 0 1 4-7m.5 3.5v3M6 13h3m7-1h.01M18 14h.01");
}

</style>
