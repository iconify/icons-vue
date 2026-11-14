<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt_4xjgar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-de-icing" /></template>
<style>
.qt_4xjgar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 2.5v17M3.75 6.75l11.646 6.827M3.75 15.25l14.5-8.5M8.75 3L11 5l2.25-2m3.5 2l-.5 3L19 9m-7.021 8.871L11 17l-2.25 2M3 13l2.75 1l-.5 3m0-12l.5 3L3 9m15 5.5v7M14.5 19l3.5-2.25L21.5 19");
}

</style>
