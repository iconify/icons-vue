<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l2_s-p9jh"/><path class="si44znbed"/><path class="h1f2yzbjx"/><path class="srf482-ro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:embedding-drift-duotone-regular" /></template>
<style>
.h1f2yzbjx {
  d: path("M8.5 5 11 7.5l-4 4 -4 -4L5.5 5");
}

.l2_s-p9jh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.5 5 11 7.5l-4 4 -4 -4L5.5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.si44znbed {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 14 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.srf482-ro {
  d: path("m10 14 3 3 3 -3 3 3");
}

</style>
