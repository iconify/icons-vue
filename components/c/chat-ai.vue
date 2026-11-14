<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmwu-cp2a"/><path class="vg30mcmob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chat-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmwu-cp2a {
  d: path("M4.5 3h15a2 2 0 0 1 2 2v10.5a2 2 0 0 1-2 2h-9L6 21v-3.5H4.5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2");
}

.vg30mcmob {
  d: path("M9.625 8.5h4.75A2.625 2.625 0 0 1 17 11.125v.75a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 7 11.875v-.75A2.625 2.625 0 0 1 9.625 8.5M12 6v2.5m-2 3h.01m3.99 0h.01");
}

</style>
