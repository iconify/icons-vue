<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ow8yl74sh"/><path class="t417hkbst"/><path class="qtp_m8b9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kangaroo-sharp" /></template>
<style>
.ow8yl74sh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.25V5.625l1.5-.375l2-.5l.75-1.25l.75-1.5v3.5l1.5.9V9l4.074.741L15.25 14l.25 2.25l.412 1.647L17.75 19l1.75 1l.5 1h-1l-2.75-.5l-2.344-.391L13 18.75V20H6.5l1.5-.75L10.25 18l-2.5-2.083V9L6 8.5l-1.75-.35z");
}

.qtp_m8b9k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 6.75h.01");
}

.t417hkbst {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 11L6.5 12.5v1");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
