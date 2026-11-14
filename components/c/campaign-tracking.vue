<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="afoihn32h"/><path class="chdpn154b"/><path class="st8bpl8_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campaign-tracking" /></template>
<style>
.afoihn32h {
  d: path("M11.987 13.847L7 11.5H2.5V7H7l8.5-4.5v9.182");
}

.chdpn154b {
  d: path("m4.5 11.5l1.25 5h2.5l-.5-4.75m7 2.75v6.75h6.75");
}

.st8bpl8_q {
  d: path("m16.75 19l1.5-2.25L19.5 18l2-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
