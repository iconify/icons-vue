<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ynls3t84z"/><path class="i8j4g7-ov"/><path class="wjj8_yb8n"/><path class="xj_u41y2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevrons-left-duotone-regular" /></template>
<style>
.i8j4g7-ov {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20 4 -8 8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wjj8_yb8n {
  d: path("m11 4 -8 8 8 8");
}

.xj_u41y2v {
  d: path("m20 4 -8 8 8 8");
}

.ynls3t84z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m11 4 -8 8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
