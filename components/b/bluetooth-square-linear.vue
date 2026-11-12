<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jjzwogv5r"/><path class="hyyb83bqk"/><path class="pw8f5c0fp"/><path class="si3inpc3v"/><path class="i70bgdbfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-square-linear" /></template>
<style>
.hyyb83bqk {
  d: path("M13.9333 15.8L12.6 16.8C11.9019 17.3236 11.5528 17.5854 11.2764 17.4472C11 17.309 11 16.8727 11 16V12L13.9333 14.2C14.4222 14.5667 14.6667 14.75 14.6667 15C14.6667 15.25 14.4222 15.4333 13.9333 15.8Z");
}

.i70bgdbfl {
  d: path("M11 12L8 14.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jjzwogv5r {
  d: path("M13.9333 9.8L11 12V8C11 7.12733 11 6.69099 11.2764 6.55279C11.5528 6.41459 11.9019 6.6764 12.6 7.2L13.9333 8.2C14.4222 8.56667 14.6667 8.75 14.6667 9C14.6667 9.25 14.4222 9.43334 13.9333 9.8Z");
}

.pw8f5c0fp {
  d: path("M2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12Z");
}

.si3inpc3v {
  d: path("M11 12L8 9.5");
}

</style>
