<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m87awbc9e"/><path class="t6i0xlblk"/><path class="u3knxkomh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dove-peace" /></template>
<style>
.m87awbc9e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.56 9.75l1.88-.56a2.25 2.25 0 0 1 3.75-.57c1.5-2.06 3.75-3.37 7.5-3.37c-.38 2.81-2.06 4.88-4.12 5.81l4.69 2.44l-2.25.94c-1.31 1.88-3.56 2.81-5.81 2.62s-3.56-1.88-3.56-4.12v-2.25Z");
}

.t6i0xlblk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.94 9.94h.01");
}

.u3knxkomh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.56 10.35C5.56 10.75 4 12.5 3 15m2.5-2.4l-1-2m-.4 3.45l1.5 1.55");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
