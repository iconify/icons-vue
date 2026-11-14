<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz6m9rjkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bleach-allowed" /></template>
<style>
.zz6m9rjkk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.517 6.134l6.473 11.243A1.75 1.75 0 0 1 18.473 20H5.527a1.75 1.75 0 0 1-1.517-2.623l6.473-11.243a1.75 1.75 0 0 1 3.034 0");
}

</style>
