<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t83h6ubaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:greenhouse-shade" /></template>
<style>
.t83h6ubaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21v-9a9 9 0 0 1 18 0v9Zm.5-11.5L15 21M9.5 3.5L21 15m-.5-5.5L9 21m5.5-17.5L3 15");
}

</style>
