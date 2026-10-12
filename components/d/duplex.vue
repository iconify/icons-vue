<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yc6mryo0n"/><path class="rfbtt9bff"/><path class="tqr73-n6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:duplex" /></template>
<style>
.rfbtt9bff {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.38 11.5h.01m9.24 0h.01");
}

.tqr73-n6o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 21.25v-4.5h2.5v4.5m5.5 0v-4.5h2.5v4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yc6mryo0n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.35v-9.2q0-.9.56-1.6L6.82 5.2q.56-.7 1.17-.04l3.4 3.68q.61.66 1.22 0l3.41-3.68q.61-.66 1.17.04l3.5 4.35q.56.7.56 1.6v9.2q0 .9-.9.9H3.65q-.9 0-.9-.9M12 11.5v9.75");
}

</style>
