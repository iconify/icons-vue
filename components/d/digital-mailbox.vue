<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k3f54ndjx"/><path class="fvd9ofblh"/><path class="xj2shibjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-mailbox" /></template>
<style>
.fvd9ofblh {
  d: path("M9.75 6.5h4.5A1.75 1.75 0 0 1 16 8.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 10.75v-2.5A1.75 1.75 0 0 1 9.75 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3f54ndjx {
  d: path("M4 15.5v-10a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v10m-17.5 4l1.5-4h16l1.5 4Z");
}

.xj2shibjb {
  d: path("M8.25 7L12 9.75L15.75 7");
}

</style>
