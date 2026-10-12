<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vol85q2ce"/><path class="icnxmkbwj"/><path class="lbi90ci2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cuckoo-clock" /></template>
<style>
.icnxmkbwj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 12.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M9.5 18v1.75m5-1.75v1.25");
}

.lbi90ci2c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 20.75h.01m4.99-.5h.01");
}

.vol85q2ce {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.6 3.45l6.8 5.1q.6.45-.15.45h-.5Q18 9 18 9.75v7.5q0 .75-.75.75H6.75Q6 18 6 17.25v-7.5Q6 9 5.25 9h-.5Q4 9 4.6 8.55l6.8-5.1q.6-.45 1.2 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
