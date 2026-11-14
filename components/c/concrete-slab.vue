<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmjq0fbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:concrete-slab" /></template>
<style>
.mmjq0fbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 9h13.75a2.625 2.625 0 0 1 2.625 2.625v4.75A2.625 2.625 0 0 1 18.875 19H5.125A2.625 2.625 0 0 1 2.5 16.375v-4.75A2.625 2.625 0 0 1 5.125 9M5.5 9V7.5a2 2 0 0 1 4 0V9m5 0V7.5a2 2 0 0 1 4 0V9");
}

</style>
