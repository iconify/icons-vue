<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhccv-bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anonymous-user" /></template>
<style>
.lhccv-bki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-3 13c0-3.5 3-6 7-6s7 2.5 7 6m.25-6.75A2.5 2.5 0 1 1 20.5 16c-.75.5-1.25 1-1.25 2m0 2.75h.01");
}

</style>
