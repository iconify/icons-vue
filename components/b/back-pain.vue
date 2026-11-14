<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7p9c11pt"/><path class="z03w9ibyp"/><path class="v1rt7tbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:back-pain" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r7p9c11pt {
  d: path("M9.5 2.5c0 1.75-1.25 2.5-3 3L5 6c-1.25.5-1.75 1.25-1.5 2.5l2.25 5c.25 1-.5 4-.5 8h13.5c0-4-.75-7-.5-8l2.25-5c.25-1.25-.25-2-1.5-2.5l-1.5-.5c-1.75-.5-3-1.25-3-3M12 5v4.5");
}

.v1rt7tbse {
  d: path("m5.5 19.5l1.5 1m11.5-1l-1.5 1");
}

.z03w9ibyp {
  fill: currentColor;
  d: path("m13.25 11.25l.25 3l3 .25l-2.25 1.75l1 2.75l-2.75-1l-1.75 2.25l-.25-3l-3-.25l2.25-1.75l-1-2.75l2.75 1Z");
}

</style>
