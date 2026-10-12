<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="evjypunfh"/><path class="upvac8alr"/><rect class="c8nlvku1g"/><path class="jr3o87bug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:holi-colors" /></template>
<style>
.c8nlvku1g {
  width: 18.5px;
  height: 2.75px;
  x: 2.75px;
  y: 18.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.evjypunfh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 18.5c.75-3 2-5.5 3.25-5.5s2.5 2.5 3.25 5.5Zm11 0c.75-3 2-5.5 3.25-5.5s2.5 2.5 3.25 5.5Z");
}

.jr3o87bug {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 9.5h.01m10.99 0h.01M12 7h.01M9 5h.01M15 4.5h.01");
}

.upvac8alr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 18.5c1-4 2.5-7.25 4.25-7.25s3.25 3.25 4.25 7.25Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
