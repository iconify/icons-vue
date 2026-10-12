<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dtodvcblf"/><path class="wv1d60b4r"/><path class="ehk1y65_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-melting" /></template>
<style>
.dtodvcblf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12a9.25 9.25 0 0 1 18.5 0c0 2-.75 3.25-1.5 4.25s.25 1.5 1 2s.5 1.5-1 1.5H15.5v.5a1 1 0 0 1-2 0v-.5h-5a.75.75 0 0 1-1.5 0H4.25c-1.5 0-1.75-1-1-1.5s1.5-1.25 1-2.25c-.75-1-1.5-1.75-1.5-4");
}

.ehk1y65_w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 13.75c1.25.75 2.75 1 4.25.5s2.25-1 2.75-2");
}

.wv1d60b4r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9.75h.01m5.99.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
