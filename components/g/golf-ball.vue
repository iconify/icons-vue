<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q268ak7kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-ball" /></template>
<style>
.q268ak7kr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.25a7 7 0 1 0 14 0a7 7 0 1 0-14 0M8.5 19h7M12 19v2.5m-3.25-12h.01M12 7.75h.01m3.24 1.75h.01m-5.01 3.25h.01m3.49 0h.01");
}

</style>
