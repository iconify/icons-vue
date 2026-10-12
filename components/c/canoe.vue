<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlkjz-b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:canoe" /></template>
<style>
.jlkjz-b8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25C4 17.5 7.5 20.5 12 20.5s8-3 9.25-7.25C20.25 14.5 19 15 17.75 15H6.25c-1.25 0-2.5-.5-3.5-1.75m12.75-10L13.6 7.4m.17.48l.16.54q.17.58-.12 1.1l-1.32 2.36q-.29.52-.83.26l-.82-.38q-.54-.26-.3-.81l1.02-2.4q.24-.55.8-.77l.68-.26q.56-.22.73.36");
}

</style>
