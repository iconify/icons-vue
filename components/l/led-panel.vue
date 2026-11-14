<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0ncp057n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:led-panel" /></template>
<style>
.s0ncp057n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3h13.75A2.625 2.625 0 0 1 21.5 5.625v5.75A2.625 2.625 0 0 1 18.875 14H5.125A2.625 2.625 0 0 1 2.5 11.375v-5.75A2.625 2.625 0 0 1 5.125 3M6.5 14v3h11v-3M12 17v4.5M8 6.75h.01m7.99 0h.01M8 10.25h.01m7.99 0h.01");
}

</style>
