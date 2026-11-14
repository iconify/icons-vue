<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qp2iq3piv"/><path class="xv09xbcqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:altimeter-setting" /></template>
<style>
.qp2iq3piv {
  d: path("M4 10.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xv09xbcqc {
  d: path("M10.5 18.5h3v3h-3ZM7.25 7.75L5 6.5M12 5V2.5m4.75 5.25L19 6.5m-7 4L10 7m2 3.5h.01");
}

</style>
