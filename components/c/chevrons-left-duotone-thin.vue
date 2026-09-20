<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rjp3akbhk"/><path class="xliyk6b3u"/><path class="wjj8_yb8n"/><path class="xj_u41y2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevrons-left-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjp3akbhk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 4 -8 8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wjj8_yb8n {
  d: path("m11 4 -8 8 8 8");
}

.xj_u41y2v {
  d: path("m20 4 -8 8 8 8");
}

.xliyk6b3u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 4 -8 8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
