<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z7ud1-bat"/><path class="se971gh0e"/><path class="qdxj-lf1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dragon-dance" /></template>
<style>
.qdxj-lf1w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h2.5M9 8c1.5-3 3.75-3 5 0s3.75 3 5 0m-7.5-2.25v15.5m5-11v11");
}

.se971gh0e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 7h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z7ud1-bat {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 5l1.5-2.25M3.32 6.01l.61-.52Q4.5 5 5.25 5H7.5q.75 0 .93.73l.39 1.54q.18.73 0 1.46l-.39 1.54q-.18.73-.93.73H4.25q-.75 0-.87-.74l-.51-3.02q-.12-.74.45-1.23");
}

</style>
