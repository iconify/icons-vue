<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzp6esnyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:letter-writing" /></template>
<style>
.zzp6esnyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2 14c0-3.75 2.25-6.5 5-6.5s5 2.75 5 6.5m2.25-4l4.5-9a1.4 1.4 0 0 1 2.5 1.25l-4.5 9L15 20Zm3 4.5h3.5");
}

</style>
