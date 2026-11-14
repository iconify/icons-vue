<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhp-gmpza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:forest" /></template>
<style>
.yhp-gmpza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h19M4.75 21v-3.5m-2.25 0L4.75 9L7 17.5ZM12 21v-3.5m-2.25 0L12 2.5l2.25 15Zm9.5 3.5v-3.5m-2.25 0L19.25 6l2.25 11.5Z");
}

</style>
