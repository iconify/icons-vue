<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrx3sobmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accountant-chat" /></template>
<style>
.qrx3sobmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-1 10.5c0-2.5 2-4 4.5-4s4.5 1.5 4.5 4m3.5-19h4.5a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H17L14.5 13v-2.5h.5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Z");
}

</style>
