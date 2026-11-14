<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t3u29z1pm"/><path class="tl9ponnkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crypto-wallet" /></template>
<style>
.t3u29z1pm {
  d: path("M2.5 7h19v13.5h-19ZM11 7a4 4 0 0 1 8 0");
}

.tl9ponnkw {
  d: path("M21.5 11.5h-4a2.25 2.25 0 0 0 0 4.5h4m-3.75-2.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
