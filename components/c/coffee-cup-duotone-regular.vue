<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c8opk6jjb"/><path class="qz457rbwx"/><path class="m5m1km1et"/><path class="zkx1g3b3t"/><path class="ghpezkxlh"/><path class="v3xsaib0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coffee-cup-duotone-regular" /></template>
<style>
.c8opk6jjb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7v9h11V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ghpezkxlh {
  d: path("M15 7a3 3 0 0 1 0 6");
}

.m5m1km1et {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qz457rbwx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 7a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v3xsaib0o {
  d: path("M2 19h15");
}

.zkx1g3b3t {
  d: path("M4 7v9h11V7");
}

</style>
