<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emp4utdsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bathtub" /></template>
<style>
.emp4utdsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.25h18.5v3a5 5 0 0 1-5 5h-8.5a5 5 0 0 1-5-5Zm3.75 8l-.75 2m11.75-2l.75 2m-12.75-10v-6a2.5 2.5 0 0 1 4.75-1.1");
}

</style>
