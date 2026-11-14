<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tvtw0tbeg"/><path class="cqg1wpi8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-on-call" /></template>
<style>
.cqg1wpi8h {
  d: path("M4 11.5V9a5 5 0 0 1 10 0v1.5m-10 1c0 1.25.75 2 2.25 2m8.495-9.321a7.5 7.5 0 0 1 0 9.642m2.651-10.7a10.25 10.25 0 0 1 0 11.758");
}

.tvtw0tbeg {
  d: path("M2.5 20c0-2.75 2.9-4.5 6.5-4.5s6.5 1.75 6.5 4.5c0 .6-.4 1-1 1h-11c-.6 0-1-.4-1-1Zm4-11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
