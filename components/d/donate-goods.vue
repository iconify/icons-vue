<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yus98ybyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-goods" /></template>
<style>
.yus98ybyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 13h9.75a2.625 2.625 0 0 1 2.625 2.625v2.25a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 17.875v-2.25A2.625 2.625 0 0 1 7.125 13M2.25 10.5L4.5 13m15 0l2.25-2.5m-15-7h1A1.75 1.75 0 0 1 9.5 5.25v3A1.75 1.75 0 0 1 7.75 10h-1A1.75 1.75 0 0 1 5 8.25v-3A1.75 1.75 0 0 1 6.75 3.5M9.5 5.25h.5a1.75 1.75 0 0 1 0 3.5h-.5m6.75-5.25h.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 16.75 10h-.5a1.75 1.75 0 0 1-1.75-1.75v-3a1.75 1.75 0 0 1 1.75-1.75M14.5 6.25h4");
}

</style>
