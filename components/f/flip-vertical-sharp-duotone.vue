<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="j30_d7qgp"/><path class="f1avybc6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-vertical-sharp-duotone" /></template>
<style>
.f1avybc6s {
  d: path("M23 12L19 12M17 12L13 12M11 12L7 12M5 12L1 12");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j30_d7qgp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M17.7682 2.6401L12.7682 8.6401C12.5782 8.8681 12.2968 8.9999 12 8.9999C11.7032 8.9999 11.4218 8.8681 11.2318 8.6401L6.2318 2.6401C6.0819 2.4604 5.9999 2.2338 5.9999 1.9998C5.9999 1.4474 6.4477 0.9997 7.0001 0.9999L16.9999 0.9999C17.5523 0.9997 18.0001 1.4474 18.0001 1.9998C18.0001 2.2338 17.9181 2.4604 17.7682 2.6401ZM17.7682 21.3599L12.7682 15.3599C12.5782 15.1319 12.2968 15 12 15C11.7032 15 11.4218 15.1319 11.2318 15.3599L6.2318 21.3599C6.0819 21.5396 5.9999 21.7662 5.9999 22.0002C5.9999 22.5526 6.4477 23.0003 7.0001 23.0001L16.9999 23.0001C17.5523 23.0003 18.0001 22.5526 18.0001 22.0002C18.0001 21.7662 17.9181 21.5396 17.7682 21.3599Z");
  stroke: none;
}

</style>
