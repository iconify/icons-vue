<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="v0_ggobvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-square-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0_ggobvf {
  d: path("M11 12L13.9333 9.8C14.4222 9.43334 14.6667 9.25 14.6667 9C14.6667 8.75 14.4222 8.56667 13.9333 8.2L12.6 7.2C11.9019 6.6764 11.5528 6.41459 11.2764 6.55279C11 6.69099 11 7.12733 11 8V12ZM11 12V16C11 16.8727 11 17.309 11.2764 17.4472C11.5528 17.5854 11.9019 17.3236 12.6 16.8L13.9333 15.8C14.4222 15.4333 14.6667 15.25 14.6667 15C14.6667 14.75 14.4222 14.5667 13.9333 14.2L11 12ZM11 12L8 9.5M11 12L8 14.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

</style>
