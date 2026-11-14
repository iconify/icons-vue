<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he329verj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:double-decker-jet" /></template>
<style>
.he329verj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 8.5 0 1 0 19 0a9.5 8.5 0 1 0-19 0m0 0h19m-15-3h.01M17.5 9h.01M6.5 15h.01m10.99 0h.01");
}

</style>
