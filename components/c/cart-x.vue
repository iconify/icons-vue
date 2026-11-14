<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ohmm7ghkt"/><path class="t8nv-ac2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cart-x" /></template>
<style>
.ohmm7ghkt {
  d: path("M5.25 7H20.5l-1.25 5.25h-7V15H7Z");
}

.t8nv-ac2c {
  d: path("M2.5 3.5h2L7 15m0 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.5-3.5l5 5m0-5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
