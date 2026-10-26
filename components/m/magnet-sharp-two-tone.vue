<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="murak4v1n"/><path class="lo3w1ac-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:magnet-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lo3w1ac-z {
  d: path("M4 13L4 3L9 3L9 13C9 14.6569 10.3431 16 12 16C13.6569 16 15 14.6569 15 13L15 3L20 3L20 13C20 17.4183 16.4183 21 12 21C7.5817 21 4 17.4183 4 13ZM4 7L9 7M15 7L20 7");
}

.murak4v1n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13L3 3C3 2.4477 3.4477 2 4 2L9 2C9.5523 2 10 2.4477 10 3L10 13C10 14.1046 10.8954 15 12 15C13.1046 15 14 14.1046 14 13L14 3C14 2.4477 14.4477 2 15 2L20 2C20.5523 2 21 2.4477 21 3L21 13C21.001 16.3261 19.1673 19.3814 16.2316 20.9449C14.9281 21.6383 13.4743 22.001 11.9978 22.001C11.2516 22.001 10.5082 21.9083 9.7847 21.7251C6.5867 20.9105 4.0895 18.4133 3.2749 15.2153C3.0919 14.4911 2.9995 13.747 3 13Z");
  stroke: none;
}

</style>
