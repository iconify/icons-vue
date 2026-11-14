<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owt5dybdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beard-brush" /></template>
<style>
.owt5dybdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.389 5.611za4 4 0 0 1 0 5.657l-2.121 2.121a4 4 0 0 1-5.657 0a4 4 0 0 1 0-5.657l2.121-2.121a4 4 0 0 1 5.657 0m-8.03 8.03za1.5 1.5 0 0 1 0 2.122l-4.596 4.596a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122l4.596-4.596a1.5 1.5 0 0 1 2.122 0M16.75 7.25h.01M14.5 9.5h.01m-2.26 2.25h.01");
}

</style>
