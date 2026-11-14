<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naadlm0wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:event-funnel" /></template>
<style>
.naadlm0wh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.805 7h8.39a1.75 1.75 0 0 1 1.329 2.889l-3.103 3.619A1.75 1.75 0 0 0 14 14.647v3.117A1.382 1.382 0 0 1 12 19l-1.033-.516A1.75 1.75 0 0 1 10 16.918v-2.271a1.75 1.75 0 0 0-.421-1.139L6.476 9.889A1.75 1.75 0 0 1 7.805 7M7 3.5h.01m4.99 0h.01m4.99 0h.01");
}

</style>
