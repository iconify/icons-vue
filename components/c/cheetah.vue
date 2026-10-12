<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wczcp4b1r"/><path class="aqagjmb7z"/><path class="lr6id3byi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cheetah" /></template>
<style>
.aqagjmb7z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 12.25C9 14 9.5 15.75 11 16.75m3.75-4.5c.25 1.75-.25 3.5-1.75 4.5");
}

.lr6id3byi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 11.25h.01m5.49 0h.01");
}

.wczcp4b1r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 9l-.25-3.75c0-.75.75-1.25 1.4-.85L9.5 6c.8-.25 1.65-.4 2.5-.4s1.7.15 2.5.4l2.85-1.6c.65-.4 1.4.1 1.4.85L18.5 9c1 1.25 1.5 2.75 1.5 4.25v1.25l1 1.25l-1.75.25c-1.25 3.25-4 5-7.25 5s-6-1.75-7.25-5L3 15.75l1-1.25v-1.25c0-1.5.5-3 1.5-4.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
