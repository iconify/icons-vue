<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us6pfqg6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:award-ceremony" /></template>
<style>
.us6pfqg6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21v-5.5h6v-3h7V17h6v4Zm6-18.5h7v3a3.5 3.5 0 0 1-7 0ZM12 9v3.5");
}

</style>
