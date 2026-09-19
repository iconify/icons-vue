<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ie5-y4ark"/><path class="dm7hc0bti"/><path class="m11alqlmi"/><path class="iq3iye03x"/><path class="k_eab8bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-school" /></template>
<style>
.dm7hc0bti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.932 29.29H9.688v-3.111m5.6-3.111h-1.244v-3.11m-3.112 3.11H9.688v-3.11m28.624 9.332h-1.244v-3.111m-3.112 3.111h-1.244v-3.111m5.6-3.111h-1.244v-3.11m-3.112 3.11h-1.244v-3.11m-15.905-4.463h1.233v1.972H6.89l2.473-3.943h9.763zm14.386 0h-1.23v1.972h11.15l-2.473-3.943h-9.764z");
}

.ie5-y4ark {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.115 34.991h9.308c.892 0 1.615.723 1.615 1.615v2.015H5.5v-2.015c0-.892.723-1.615 1.615-1.615m24.462 0h9.308c.892 0 1.615.723 1.615 1.615v2.015H29.962v-2.015c0-.892.723-1.615 1.614-1.615m-24.688 0V17.47h11.15m11.924 0h11.15v17.52m-25.824-5.7h-1.244v-3.111");
}

.iq3iye03x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.04 15.495h11.92v23.129H18.04z");
}

.k_eab8bev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.548 28.02h6.905v8.184h-6.905z");
}

.m11alqlmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.193 15.495H16.806l1.234-1.047L24 9.376zM18.038 36.204h11.924m11.15 2.417H6.888M24 36.204v-8.185m0-5.951v-2.682m0 2.682l1.341-.67M14.044 34.991v-2.59m-4.356 2.59v-2.59m27.38 2.59v-2.59m-4.356 2.59v-2.59M19.955 21.757a4.044 4.044 0 0 0 8.09.002v-.002a4.044 4.044 0 0 0-8.09-.001z");
}

</style>
