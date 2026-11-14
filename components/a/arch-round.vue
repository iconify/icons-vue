<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbt6lzboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arch-round" /></template>
<style>
.lbt6lzboy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5v-10a8.5 8.5 0 0 1 17 0v10h-5v-10a3.5 3.5 0 0 0-7 0v10Zm7-13.25L8.75 3.5m4.75 4.75l1.75-4.75m-11.75 8h5m7 0h5");
}

</style>
