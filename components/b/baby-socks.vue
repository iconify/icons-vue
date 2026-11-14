<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waqrktm1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-socks" /></template>
<style>
.waqrktm1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3v13.5a4 4 0 0 1-4 4H4.5a2.5 2.5 0 0 1 0-5H6V3Zm4 0v13.5a4 4 0 0 0 4 4h1.5a2.5 2.5 0 0 0 0-5H18V3ZM6 6.5h4m4 0h4");
}

</style>
