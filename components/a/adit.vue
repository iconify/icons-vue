<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqadusiax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adit" /></template>
<style>
.kqadusiax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 2l19 5.5M2.5 21h19m-16 0v-6.5a6.5 6.5 0 0 1 13 0V21m-10 0l2.25-5m4.75 5l-2.25-5");
}

</style>
