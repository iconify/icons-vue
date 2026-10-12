<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qd6k59iig"/><path class="tlbhtf9bl"/><path class="cbrcj8fol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:landslide" /></template>
<style>
.cbrcj8fol {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.5 15.25h.01");
}

.qd6k59iig {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.05V5.95q0-1.2 1.2-1.2H6.3q1.2 0 1.97.92l12.21 14.66q.77.92-.43.92H3.95q-1.2 0-1.2-1.2");
}

.tlbhtf9bl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 11.5l4.25.75l3 4.5m7.34-8.85l1.82-.3q.59-.1.8.46l.58 1.63q.21.56-.32.85l-1.69.92q-.53.29-.72-.28l-.87-2.61q-.19-.57.4-.67");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
