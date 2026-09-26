<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6on06uxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-scatter-bubble" /></template>
<style>
.m6on06uxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21M20 6C20 7.6569 18.6569 9 17 9C15.3431 9 14 7.6569 14 6C14 4.3431 15.3431 3 17 3C18.6569 3 20 4.3431 20 6ZM11 14C11 15.1046 10.1046 16 9 16C7.8954 16 7 15.1046 7 14C7 12.8954 7.8954 12 9 12C10.1046 12 11 12.8954 11 14ZM19.5 15C19.5 15.8284 18.8284 16.5 18 16.5C17.1716 16.5 16.5 15.8284 16.5 15C16.5 14.1716 17.1716 13.5 18 13.5C18.8284 13.5 19.5 14.1716 19.5 15Z");
}

</style>
