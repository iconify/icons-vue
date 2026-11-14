<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcdps08lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broom-and-dustpan" /></template>
<style>
.dcdps08lm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5L6.25 13M2.5 21l1.75-8h4L10 21Zm10.25 0h8.75v-7c-4 0-6.5 3-8.75 7Zm-6.5-5v5m15.25-7l-1.75-4.5");
}

</style>
