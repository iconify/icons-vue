<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="su8lvkbdm"/><path class="ta_u09b7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chat-attachment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.su8lvkbdm {
  d: path("M5 2.75h14a2 2 0 0 1 2 2V15.5a2 2 0 0 1-2 2h-8L7 21v-3.5H5a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2");
}

.ta_u09b7t {
  d: path("M12 9v4a1.5 1.5 0 0 0 3 0V8.5a3 3 0 0 0-6 0v6");
}

</style>
