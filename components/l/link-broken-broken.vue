<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oezaxpo8x"/><path class="gfk6kebjy"/><path class="vvptc81kx"/><path class="ecdea3xxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-broken-broken" /></template>
<style>
.ecdea3xxa {
  d: path("M15 15.5866L10.9653 20.001C9.57254 21.5247 7.0887 21.2777 5.41744 19.4492C3.74618 17.6207 3.52038 14.9032 4.91309 13.3795L6.17395 12");
}

.gfk6kebjy {
  d: path("M6 4L8 7");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oezaxpo8x {
  d: path("M2 8L8 10");
}

.vvptc81kx {
  d: path("M11 6.56252L14.7001 2.93755C16.1597 1.50753 18.7629 1.73938 20.5145 3.4554M18.1358 12L21.043 9.15178C21.6325 8.57431 21.9453 7.81414 21.9934 7");
}

</style>
