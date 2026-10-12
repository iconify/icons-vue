<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="h6nlysfim"/><path class="m9me6bb5j"/><path class="un-laqb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:luggage-tag" /></template>
<style>
.h6nlysfim {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.18 5.67l3.39 2.66q1.18.92 1.18 2.42v9q0 1.5-1.5 1.5h-8.5q-1.5 0-1.5-1.5v-9q0-1.5 1.18-2.42l3.39-2.66q1.18-.92 2.36 0");
}

.m9me6bb5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01");
}

.un-laqb0a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5c-1.5-3.5-3.5-6-7.5-6.75M9.25 14h5.5m-5.5 3.25h3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
