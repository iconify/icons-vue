<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wir3l_cnj"/><path class="l7cfyfi7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:junction-view" /></template>
<style>
.l7cfyfi7s {
  d: path("M5 9.75V5h4.75m4.5 0H19v4.75M7.5 21.5V16L3 11.5m13.5 10V16l4.5-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wir3l_cnj {
  d: path("M12 20.5V12L5 5m7 7l7-7");
}

</style>
