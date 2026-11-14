<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3a69bb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:control-room" /></template>
<style>
.h3a69bb8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3h6v7.5H9Zm-6.5.5L6.75 5v6L2.5 12.5Zm19 0L17.25 5v6l4.25 1.5ZM2.5 17h19M9 14h6");
}

</style>
