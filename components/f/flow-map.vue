<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="boj77ab7w"/><path class="fx4rqm3pc"/><path class="i2u_r_zfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flow-map" /></template>
<style>
.boj77ab7w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.69 5.4l4.12-1.55q.94-.35 1.88-.02l4.62 1.59q.94.33 1.88-.02l4.12-1.55q.94-.35.94.65v12.75q0 1-.94 1.35l-4.12 1.55q-.94.35-1.88.02l-4.62-1.59q-.94-.33-1.88.02l-4.12 1.55q-.94.35-.94-.65V6.75q0-1 .94-1.35");
}

.fx4rqm3pc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 15.25C8 10.75 12.25 8 17.25 8.5M15 6.5l2.25 2l-1.75 2.25");
}

.i2u_r_zfr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 15.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
