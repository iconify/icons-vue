<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os9uadbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:curtain-wall" /></template>
<style>
.os9uadbuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.125 2.5h7.75A2.625 2.625 0 0 1 18.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 5.5 18.875V5.125A2.625 2.625 0 0 1 8.125 2.5M12 2.5v19M5.5 7.25h13M5.5 12h13m-13 4.75h13");
}

</style>
