<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jwcopzbqn"/><path class="oo0y9dcka"/><path class="zdwkkh4ek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cruise-ship-sharp" /></template>
<style>
.jwcopzbqn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.35 9.01l.55-4.27L10 4h3.5l.1.74l.55 4.27l.1.74h-5zm-5.6 5.24h1.5v-4.5H17.5v4.5h3.75l-.36.93l-1.78 4.64l-.36.93H5.25l-.36-.93l-1.78-4.64l-.36-.93z");
}

.oo0y9dcka {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12.25h.01m3.49 0h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zdwkkh4ek {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.25h18");
}

</style>
