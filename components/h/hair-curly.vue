<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjmxk0y0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hair-curly" /></template>
<style>
.cjmxk0y0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5c3 0 3.25 4.25.25 4.25c-1.5 0-1.5-2 0-1.75c3.25.75 3 5.75 0 5.75c-1.5 0-1.5-2 0-1.75c3.25.75 3 5.75 0 5.75c-1.5 0-1.5-2 0-1.75c3.25.75 3 6.5-.25 6.5m8-17c3 0 3.25 4.25.25 4.25c-1.5 0-1.5-2 0-1.75c3.25.75 3 5.75 0 5.75c-1.5 0-1.5-2 0-1.75c3.25.75 3 5.75 0 5.75c-1.5 0-1.5-2 0-1.75c3.25.75 3 6.5-.25 6.5");
}

</style>
