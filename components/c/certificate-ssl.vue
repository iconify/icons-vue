<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aen2wn78p"/><path class="xu6zxdb0f"/><rect class="iwlbvzbvk"/><path class="jb5ddcecn"/><path class="dwpo8vbpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:certificate-ssl" /></template>
<style>
.aen2wn78p {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.dwpo8vbpb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 17.75h.01");
}

.iwlbvzbvk {
  width: 8px;
  height: 7.25px;
  x: 13.25px;
  y: 14px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.jb5ddcecn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 14v-1.25a1.75 1.75 0 0 1 3.5 0V14");
}

.xu6zxdb0f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.75h11m-11 3.5H11");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
