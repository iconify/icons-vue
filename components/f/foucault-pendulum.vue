<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shrcpvbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foucault-pendulum" /></template>
<style>
.shrcpvbed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h12m-6 0l3.75 9m-2 3a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m7.75 4.454a19 19 0 0 1-19 0");
}

</style>
