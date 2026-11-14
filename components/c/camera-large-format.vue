<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibhyfwtkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-large-format" /></template>
<style>
.ibhyfwtkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 4.5h.5A1.75 1.75 0 0 1 6.5 6.25v9.5a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-9.5A1.75 1.75 0 0 1 4.25 4.5m15 2.5h.5a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 19.75 15h-.5a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 19.25 7M2.5 21h19M6.5 5.75l11 2.75m-11 7.75l11-2.75M12 7.25v7.5");
}

</style>
