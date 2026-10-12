<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sisi68y9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-front" /></template>
<style>
.sisi68y9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 13a1 1 0 0 1 1-1h.6L7 7.15a2 2 0 0 1 1.9-1.4h6.2a2 2 0 0 1 1.9 1.4L18.65 12h.6a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H4.75a1 1 0 0 1-1-1Zm2.75 6v2m11-2v2m-12-9h13M6.25 15.25H8.5m7 0h2.25m-7.25 0h3");
}

</style>
