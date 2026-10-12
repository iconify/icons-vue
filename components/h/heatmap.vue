<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="c02sccbys"/><rect class="d7if13bqg"/><path class="svmz4fgqz"/><rect class="c13ov7bos"/><rect class="ld4qa4-qd"/><path class="in_yp6bue"/><path class="n0mhiqb6r"/><path class="ezm81yf6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heatmap" /></template>
<style>
.c02sccbys {
  width: 4px;
  height: 4px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.c13ov7bos {
  width: 4px;
  height: 4px;
  x: 2.75px;
  y: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.d7if13bqg {
  width: 4px;
  height: 4px;
  x: 10px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.ezm81yf6g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19.25h.01m7.24 0h.01");
}

.in_yp6bue {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.25 12h.01");
}

.ld4qa4-qd {
  width: 4px;
  height: 4px;
  x: 10px;
  y: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.n0mhiqb6r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 17.25h1.5a1.25 1.25 0 0 1 1.25 1.25V20a1.25 1.25 0 0 1-1.25 1.25H4A1.25 1.25 0 0 1 2.75 20v-1.5A1.25 1.25 0 0 1 4 17.25");
}

.svmz4fgqz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 2.75H20A1.25 1.25 0 0 1 21.25 4v1.5A1.25 1.25 0 0 1 20 6.75h-1.5a1.25 1.25 0 0 1-1.25-1.25V4a1.25 1.25 0 0 1 1.25-1.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
