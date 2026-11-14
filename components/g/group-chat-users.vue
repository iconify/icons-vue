<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zulr53byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:group-chat-users" /></template>
<style>
.zulr53byf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h5a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-1.25L12 10l-1.25-1.5H9.5a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2m-5.25 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2.25 21v-.25c0-2.15 1.75-3.5 4-3.5s4 1.35 4 3.5V21m3.5 0v-.25c0-2.15 1.75-3.5 4-3.5s4 1.35 4 3.5V21");
}

</style>
