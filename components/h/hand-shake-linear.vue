<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tf_xfjxyi"/><path class="rwyyhnb2f"/><path class="qgl0b2pvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-shake-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qgl0b2pvl {
  stroke-linejoin: round;
  d: path("M8.18595 11.7548L6.50218 8.86743C6.03722 8.0701 4.9217 7.84584 4.0106 8.36655C3.0995 8.88725 2.73784 9.95573 3.2028 10.7531L6.99128 17.2497C8.85112 20.4391 13.3132 21.3361 16.9576 19.2533C20.602 17.1705 22.0487 12.8965 20.1888 9.7072L17.6632 5.37608C17.1982 4.57875 16.0827 4.35449 15.1716 4.8752C14.2605 5.3959 13.8988 6.46438 14.3638 7.26172M6.50218 8.86743L4.39747 5.25817C3.93251 4.46083 4.29417 3.39235 5.20527 2.87164C6.11637 2.35094 7.23189 2.57519 7.69685 3.37253L8.53873 4.81624M11.0644 9.14736L8.53873 4.81624C8.07377 4.0189 8.43544 2.95042 9.34654 2.42971C10.2576 1.90901 11.3732 2.13326 11.8381 2.9306L14.3638 7.26172M14.3638 7.26172L16.0475 10.1491C14.2253 11.1905 13.502 13.3275 14.4319 14.9222");
}

.rwyyhnb2f {
  d: path("M14.8252 2.18595C16.5021 1.70882 18.2333 2.16305 19.4417 3.39724");
}

.tf_xfjxyi {
  d: path("M8.78355 22C7.09836 21.2479 5.70641 20.0759 4.7915 18.5069");
}

</style>
