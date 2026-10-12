<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="nzt1986ry"/><path class="zgyor4y4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:influencer-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzt1986ry {
  cx: 9.5px;
  cy: 8.5px;
  r: 3.25px;
}

.zgyor4y4s {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75M18.14 3.07l.69 1.53q.14.32.49.35l1.66.18q.35.04.09.27l-1.24 1.13q-.26.23-.19.57l.35 1.64q.07.34-.24.17l-1.45-.84q-.3-.17-.6 0l-1.45.84q-.31.17-.24-.17l.35-1.64q.07-.34-.19-.57L14.93 5.4q-.26-.23.09-.27l1.66-.18q.35-.03.49-.35l.69-1.53q.14-.32.28 0");
}

</style>
