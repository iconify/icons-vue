<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gru8xib8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:helmet-visor-up" /></template>
<style>
.gru8xib8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 19.5v-7C3.5 7.5 7.25 4 12 4c4.25 0 7.75 3 8.5 7.5H12V15h8.5v4.5Zm9.5-11l8.5-3");
}

</style>
