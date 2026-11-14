<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ji8-ajfgu"/><path class="do09h-bka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:airport-rail-link" /></template>
<style>
.do09h-bka {
  d: path("M6.25 5.5h6V10h-6ZM7 13.75h.01m4.49 0h.01m7.24.25v7.75M15.5 19.5l3.25-2.25L22 19.5m-5 2.25h3.5");
}

.ji8-ajfgu {
  d: path("M14.342 16.94Q14.176 17 14 17H4.5q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T3.5 16V3.5q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T4.5 2.5H14q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T15 3.5V16q0 .192-.071.371q-.072.179-.204.318M7 17l-1.5 4m6-4l.562 1.498m.737 1.966L13 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
