<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gq10mkbuq"/><path class="bzlemrbpp"/><path class="zjt_73beb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diving-flag" /></template>
<style>
.bzlemrbpp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4.75 4l15 10.5");
}

.gq10mkbuq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.5h15a1 1 0 0 1 1 1V14a1 1 0 0 1-1 1h-15Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zjt_73beb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 21.25V2.75");
}

</style>
