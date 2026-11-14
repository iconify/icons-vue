<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmqb1_b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:infinity-symbol" /></template>
<style>
.xmqb1_b9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-2.5-3.5-6-4-7.5-2q-2.25 3 0 6c1.5 2 5 1.5 7.5-4s6-6 7.5-4q2.25 3 0 6c-1.5 2-5 1.5-7.5-2");
}

</style>
