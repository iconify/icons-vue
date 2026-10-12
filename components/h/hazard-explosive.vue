<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yms02xb-d"/><path class="qugd4lbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hazard-explosive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qugd4lbdv {
  d: path("m12.2 7.32l.6 1.71q.19.57.74.31l1.63-.79q.54-.26.28.28l-.79 1.63q-.26.55.31.74l1.71.6q.57.2 0 .4l-1.71.6q-.57.19-.31.74l.79 1.63q.26.54-.28.28l-1.63-.79q-.55-.26-.74.31l-.6 1.71q-.2.57-.4 0l-.6-1.71q-.19-.57-.74-.31l-1.63.79q-.54.26-.28-.28l.79-1.63q.26-.55-.31-.74l-1.71-.6q-.57-.2 0-.4l1.71-.6q.57-.19.31-.74l-.79-1.63q-.26-.54.28-.28l1.63.79q.55.26.74-.31l.6-1.71q.2-.57.4 0");
}

.yms02xb-d {
  d: path("m13.59 3.84l6.57 6.57q1.59 1.59 0 3.18l-6.57 6.57q-1.59 1.59-3.18 0l-6.57-6.57q-1.59-1.59 0-3.18l6.57-6.57q1.59-1.59 3.18 0");
}

</style>
