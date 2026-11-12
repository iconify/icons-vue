<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="m8po4lb0y"/><path class="swwenbbzn"/><path class="x6n06bc8k"/><path class="dlv77yj6n"/><path class="qy_bk4bmk"/><ellipse class="nhusggbmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-emoji-line-duotone" /></template>
<style>
.dlv77yj6n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.0124 4.32668L15.3532 4.98108C14.8823 5.16679 14.8823 5.83321 15.3532 6.01892L17.0124 6.67332C17.1562 6.73002 17.27 6.84382 17.3267 6.98758L17.9811 8.64684C18.1668 9.11772 18.8332 9.11772 19.0189 8.64684L19.6733 6.98758C19.73 6.84382 19.8438 6.73002 19.9876 6.67332L21.6468 6.01892C22.1177 5.83321 22.1177 5.16679 21.6468 4.98108L19.9876 4.32668C19.8438 4.26998 19.73 4.15618 19.6733 4.01242L19.0189 2.35316C18.8332 1.88228 18.1668 1.88228 17.9811 2.35316L17.3267 4.01242C17.27 4.15618 17.1562 4.26998 17.0124 4.32668Z");
}

.m8po4lb0y {
  cx: 9.5px;
  cy: 14.5px;
  r: 7.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhusggbmx {
  cx: 9px;
  cy: 12.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 0.5px;
  ry: 1px;
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.qy_bk4bmk {
  d: path("M13.5 12.5C13.5 13.0523 13.2761 13.5 13 13.5C12.7239 13.5 12.5 13.0523 12.5 12.5C12.5 11.9477 12.7239 11.5 13 11.5C13.2761 11.5 13.5 11.9477 13.5 12.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.swwenbbzn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 16L12 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.x6n06bc8k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 7L15 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
