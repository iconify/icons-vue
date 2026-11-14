<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnnqo87aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-pack-aa" /></template>
<style>
.nnnqo87aw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 4.5h.75A2.625 2.625 0 0 1 10.5 7.125v11.25A2.625 2.625 0 0 1 7.875 21h-.75A2.625 2.625 0 0 1 4.5 18.375V7.125A2.625 2.625 0 0 1 7.125 4.5m9 0h.75A2.625 2.625 0 0 1 19.5 7.125v11.25A2.625 2.625 0 0 1 16.875 21h-.75a2.625 2.625 0 0 1-2.625-2.625V7.125A2.625 2.625 0 0 1 16.125 4.5M7.5 2.5v2m9-2v2m-14 8.25h19");
}

</style>
