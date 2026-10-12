<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e-j_1wb-i"/><path class="g520vdb1j"/><rect class="mfxipeb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lantern-fanoos" /></template>
<style>
.e-j_1wb-i {
  d: path("M12 2.75v2m.35.35l3.05 3.05q.35.35-.15.35h-6.5q-.5 0-.15-.35l3.05-3.05q.35-.35.7 0m-4.1 3.4h7.5q.75 0 .97.72l1.06 3.56q.22.72-.12 1.39l-1.82 3.66q-.34.67-1.09.67h-5.5q-.75 0-1.09-.67l-1.82-3.66q-.34-.67-.12-1.39l1.06-3.56q.22-.72.97-.72");
}

.g520vdb1j {
  d: path("M10.6 11h2.8q.6 0 .81.56l.58 1.63q.21.56-.1 1.07l-.88 1.48q-.31.51-.91.51h-1.8q-.6 0-.91-.51l-.88-1.48q-.31-.51-.1-1.07l.58-1.63Q10 11 10.6 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mfxipeb9g {
  width: 5px;
  height: 2.5px;
  x: 9.5px;
  y: 18.5px;
  rx: 0.75px;
}

</style>
