<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bw1t57bti"/><path class="p1o66tbln"/><path class="hwufvfb8q"/><path class="y7d5mpfbz"/><path class="y334m4yqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-front-duotone-regular" /></template>
<style>
.bw1t57bti {
  fill: currentColor;
  d: path("M3 20v-8l9 -9 9 9v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hwufvfb8q {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p1o66tbln {
  fill: currentColor;
  d: path("M9 8h6v4H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y334m4yqh {
  d: path("M9 8h6v4H9Z");
}

.y7d5mpfbz {
  d: path("M10 20v-5h4v5");
}

</style>
