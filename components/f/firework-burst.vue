<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj8f-8j2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:firework-burst" /></template>
<style>
.aj8f-8j2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.75V8.5m0 7v2.75M5.75 12H8.5m7 0h2.75M14.5 9.5l2-2m-7 2l-2-2m7 7l2 2m-7-2l-2 2m4.5-14h.01m-.01 19h.01M2.5 12h.01m18.99 0h.01m-2.76-6.75h.01m-13.51 0h.01m13.49 13.5h.01m-13.51 0h.01");
}

</style>
