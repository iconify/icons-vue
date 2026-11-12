<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nerijcc5y"/><path class="fsxwe0nbu"/><path class="girv7pn6s"/><path class="n-dhbzbjq"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:full-screen-square-broken" /></template>
<style>
.fsxwe0nbu {
  d: path("M6 14.0002C6.01447 15.7067 6.10921 16.6475 6.72963 17.2679C7.35004 17.8883 8.29083 17.9831 9.99739 17.9976");
}

.girv7pn6s {
  d: path("M17.998 9.99739C17.9836 8.29083 17.8888 7.35004 17.2684 6.72963C16.648 6.10921 15.7072 6.01447 14.0007 6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-dhbzbjq {
  d: path("M17.998 14.0002C17.9836 15.7067 17.8888 16.6475 17.2684 17.2679C16.648 17.8883 15.7072 17.9831 14.0007 17.9976");
}

.nerijcc5y {
  d: path("M6 9.99739C6.01447 8.29083 6.10921 7.35004 6.72963 6.72963C7.35004 6.10921 8.29083 6.01447 9.99739 6");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

</style>
