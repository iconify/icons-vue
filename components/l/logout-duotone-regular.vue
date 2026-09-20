<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yf9gwfh6d"/><path class="gbmxeebre"/><path class="fz5xni2mc"/><path class="wt76_hbmn"/><path class="g9c4ykb9u"/><path class="m27ljac1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logout-duotone-regular" /></template>
<style>
.fz5xni2mc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g9c4ykb9u {
  d: path("M11 12h10");
}

.gbmxeebre {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m27ljac1c {
  d: path("m18 9 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wt76_hbmn {
  d: path("M9 3H3v18h6");
}

.yf9gwfh6d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 3H3v18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
