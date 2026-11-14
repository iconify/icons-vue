<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f92jmacmh"/><path class="bha7wobmx"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auto-reply" /></template>
<style>
.bha7wobmx {
  d: path("m2.5 7.5l8.5 5l8.5-5m1.25 11A2.75 2.75 0 1 1 18 15.75");
}

.f92jmacmh {
  d: path("M12.6 17H2.5V4h17v8.9");
}

.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
