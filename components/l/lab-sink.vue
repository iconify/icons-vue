<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mga99xdbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-sink" /></template>
<style>
.mga99xdbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18v1.5a6 6 0 0 1-6 6H9a6 6 0 0 1-6-6Zm9 7.5v3M8 11V6a3 3 0 0 1 6 0v1.5");
}

</style>
