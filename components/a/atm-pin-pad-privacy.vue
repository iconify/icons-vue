<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-ntbxvea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atm-pin-pad-privacy" /></template>
<style>
.x-ntbxvea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8L5 3h14l2.5 5Zm7 2.75h5a3.5 3.5 0 0 1 3.5 3.5v4.25a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 18.5v-4.25a3.5 3.5 0 0 1 3.5-3.5m-.5 3h.01m2.99 0h.01m2.99 0h.01M9 16.5h.01m2.99 0h.01m2.99 0h.01M9 19.25h.01m2.99 0h.01m2.99 0h.01");
}

</style>
