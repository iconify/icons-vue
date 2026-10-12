<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qz6pmd6mx"/><path class="d4f18hyjm"/><path class="nk-di3bjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:halloween-pumpkin" /></template>
<style>
.d4f18hyjm {
  d: path("M12 6.5c-1-.6-2.1-.75-3.25-.75C5.25 5.75 3 9.25 3 13.5s2.25 7.75 5.75 7.75c1.25 0 2.25-.4 3.25-1c1 .6 2 1 3.25 1c3.5 0 5.75-3.5 5.75-7.75s-2.25-7.75-5.75-7.75c-1.15 0-2.25.15-3.25.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk-di3bjz {
  d: path("M7.25 12.25L8.75 10l1.5 2.25Zm6.5 0l1.5-2.25l1.5 2.25ZM7 15.5l1.6 1.6l1.6-1.35L12 17.1l1.8-1.35l1.6 1.35l1.6-1.6");
}

.qz6pmd6mx {
  d: path("M12 6.25c0-1.75.75-3 2.25-3.5");
}

</style>
