<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o68y57bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:combustion" /></template>
<style>
.o68y57bhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c2 3.5 5.5 5.5 5.5 9.5a5.5 5.5 0 0 1-11 0c0-3 1.5-5 3-6c0 2.5.75 3.5 1.75 4c-.5-3-.25-5 .75-7.5M7 21h10");
}

</style>
