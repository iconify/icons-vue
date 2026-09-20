<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d9g8ihdrs"/><path class="ypkw97edh"/><path class="h1f2yzbjx"/><path class="srf482-ro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:embedding-drift-duotone-bold" /></template>
<style>
.d9g8ihdrs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 5 11 7.5l-4 4 -4 -4L5.5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h1f2yzbjx {
  d: path("M8.5 5 11 7.5l-4 4 -4 -4L5.5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srf482-ro {
  d: path("m10 14 3 3 3 -3 3 3");
}

.ypkw97edh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 14 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
