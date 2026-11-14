<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9zvjmblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-systems" /></template>
<style>
.r9zvjmblw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.436 19.5h-.186c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l1.781 2.226m-2.003 1.451a1.8 1.8 0 0 1-.278-.427L12 12l.5 2l.293 1.659M7.25 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11.522 10.463l1.103.662a1.312 1.312 0 0 1 0 2.25l-1.103.662a1.5 1.5 0 0 1-1.544 0l-1.103-.662a1.312 1.312 0 0 1 0-2.25l1.103-.662a1.5 1.5 0 0 1 1.544 0M14.25 19.5L18 21.75l3.75-2.25");
}

</style>
