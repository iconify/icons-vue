<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ptzwm-gyk"/><path clip-rule="evenodd" class="qa3eiybug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alert-double-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ptzwm-gyk {
  d: path("M9 4V16M15 4V16");
}

.qa3eiybug {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 19C10 19.5523 9.552 20 9 20C8.448 20 8 19.5523 8 19C8 18.4477 8.448 18 9 18C9.552 18 10 18.4477 10 19ZM16 19C16 19.5523 15.552 20 15 20C14.448 20 14 19.5523 14 19C14 18.4477 14.448 18 15 18C15.552 18 16 18.4477 16 19Z");
  stroke: none;
}

</style>
