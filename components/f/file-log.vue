<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yjt4258yu"/><path class="x1o31cg7c"/><path class="kddx26bfs"/><path class="u81zjw1kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-log" /></template>
<style>
.kddx26bfs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 11.25h.01m-.01 3h.01m-.01 3h.01");
}

.u81zjw1kh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 11.25h4m-4 3h4m-4 3h2.5");
}

.x1o31cg7c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yjt4258yu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

</style>
