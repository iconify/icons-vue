<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j5hk4ybky"/><path class="vxkjkxmgz"/><path class="h51gqww2n"/><path class="bm68p9f0y"/><path class="wuryx9-rm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:donate-duotone-thin" /></template>
<style>
.bm68p9f0y {
  d: path("M6.5 10.5v3");
}

.h51gqww2n {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5hk4ybky {
  fill: currentColor;
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vxkjkxmgz {
  fill: currentColor;
  d: path("M14 9a2.5 2.5 0 0 1 4 0 2.5 2.5 0 0 1 4 0l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wuryx9-rm {
  d: path("M14 9a2.5 2.5 0 0 1 4 0 2.5 2.5 0 0 1 4 0l-4 4Z");
}

</style>
