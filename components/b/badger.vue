<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qpo6qvcxs"/><path class="zw9ztthdt"/><path class="ppp2pccnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badger" /></template>
<style>
.ppp2pccnu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 10.25h.01m9.99 0h.01m-5.01 7h.01");
}

.qpo6qvcxs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9.25c0-1.5.5-2.5 1.25-3.25L5.6 4.5c-.05-.55.5-.9.95-.6L8 4.9c1.25-.3 2.6-.4 4-.4s2.75.1 4 .4l1.45-1c.45-.3 1 .05.95.6L18.25 6c.75.75 1.25 1.75 1.25 3.25c0 1.25-.5 2.5-1.25 3.5l-4.75 6.5c-.75 1-2.25 1-3 0l-4.75-6.5c-.75-1-1.25-2.25-1.25-3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zw9ztthdt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14.5C10 11.5 9.25 8 8.75 5m4.75 9.5c.5-3 1.25-6.5 1.75-9.5");
}

</style>
