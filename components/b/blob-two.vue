<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inv8ykmfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blob-two" /></template>
<style>
.inv8ykmfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 8.5c1.25 0 2-2 5-2s5 2.5 5 5.75s-2 5.5-5 5.5c-2.75 0-3.5-2-5-2S9.5 19 6.5 19c-2.75 0-4-3.5-4-7s1.25-7 4-7c3 0 3.5 3.5 5 3.5m-5 3.5h.01");
}

</style>
