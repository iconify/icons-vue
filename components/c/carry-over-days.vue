<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="id55xb3hh"/><path class="s5hy7pb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carry-over-days" /></template>
<style>
.id55xb3hh {
  d: path("M12.228 21.5H5.5q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T4.5 20.5v-13q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124t.173-.093t.188-.057T5.5 6.5h13q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188t.019.195v3.586m-.554 10.309q-.211.105-.446.105h-.672M7 2.5h10v4H7ZM4.5 12h14.1M15 21.5v-2a3 3 0 0 1 3-3h3");
}

.s5hy7pb9x {
  d: path("m19.5 15l1.5 1.5l-1.5 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
