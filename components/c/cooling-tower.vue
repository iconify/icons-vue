<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spxztab8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cooling-tower" /></template>
<style>
.spxztab8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.5Q9.5 15 7.25 10.25h9.5Q14.5 15 19 21.5Zm3-14a2.5 2.5 0 0 1 3-3.25a2.5 2.5 0 0 1 4.5 1.25a1.5 1.5 0 0 1 1 2Z");
}

</style>
