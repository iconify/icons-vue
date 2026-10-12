<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tykp0sb6z"/><path class="i7l0ccctm"/><path class="bjb2xfbkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-heart-sharp" /></template>
<style>
.bjb2xfbkm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 21h-.319l-.231-.2c-1.65-1.4-3.7-3.05-3.7-5.3v-2.35h3.464l.786 1.1l.786-1.1h3.464v2.35c0 2.25-2.05 3.9-3.7 5.3l-.231.2z");
}

.i7l0ccctm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01M8 17h.01");
}

.tykp0sb6z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 20.25h-7.5v-15h16.5v6M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
