<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x560nfbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chat-transfer" /></template>
<style>
.x560nfbbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6A2.5 2.5 0 0 1 5 3.5h5A2.5 2.5 0 0 1 12.5 6v5a2.5 2.5 0 0 1-2.5 2.5H8l-3 3v-3A2.5 2.5 0 0 1 2.5 11ZM16 13.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-1.5 7.75c0-1.75 1.75-2.75 3.75-2.75s3.75 1 3.75 2.75M8 8h9.5m-2.25-2.25L17.5 8l-2.25 2.25");
}

</style>
