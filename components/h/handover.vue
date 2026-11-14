<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="smwok-9bw"/><path class="q07l9pgrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:handover" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q07l9pgrg {
  d: path("M8.375 2.75h2a1.875 1.875 0 0 1 1.875 1.875A1.875 1.875 0 0 1 10.375 6.5h-2A1.875 1.875 0 0 1 6.5 4.625A1.875 1.875 0 0 1 8.375 2.75M6.25 9.5h6.25M6.25 13h4.25m4 3H21m-1.75-1.75L21 16l-1.75 1.75M21.5 20H15m1.75-1.75L15 20l1.75 1.75");
}

.smwok-9bw {
  d: path("M12.171 17.5H4.75c-.75 0-1.5-.75-1.5-1.75V6c0-1 .75-1.75 1.5-1.75H6.5V4c0-.75.5-1.25 1.25-1.25H11c.5 0 1.25.5 1.25 1.25v.25h1.5c1 0 1.75.75 1.75 1.75v7.222");
}

</style>
