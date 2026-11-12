<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="eqqdeno9t"/><path class="h5cnh42vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-wifi-linear" /></template>
<style>
.eqqdeno9t {
  d: path("M7.88403 3.86711L5.88403 5.10837C3.98695 6.28576 3.0384 6.87445 2.5192 7.82299C2 8.77152 2 9.91573 2 12.2042V13.7252C2 17.6261 2 19.5765 3.17157 20.7884C4.34315 22.0002 6.22876 22.0002 10 22.0002H14C17.7712 22.0002 19.6569 22.0002 20.8284 20.7884C22 19.5765 22 17.6261 22 13.7252V12.2042C22 9.91573 22 8.77152 21.4808 7.82299C20.9616 6.87445 20.0131 6.28576 18.116 5.10837L16.116 3.86711C14.1106 2.62253 13.1079 2.00024 12 2.00024C10.8921 2.00024 9.88939 2.62253 7.88403 3.86711Z");
}

.h5cnh42vo {
  d: path("M6 11.6825C9.31371 8.10583 14.6863 8.10583 18 11.6825M8.00002 13.841C10.2092 11.4566 13.7909 11.4566 16 13.841M10 16C11.1046 14.8078 12.8955 14.8078 14 16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
