<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vevmidywk"/><path class="ohm6udbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-minus-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ohm6udbbk {
  d: path("M9.75 12.5L14.25 12.5");
}

.vevmidywk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 20L18 20C20.5784 20 22.734 18.0393 22.9776 15.4724C23.2212 12.9055 21.4729 10.5743 18.9405 10.0893C18.4833 6.6052 15.5139 4 12 4C8.4861 4 5.5167 6.6052 5.0595 10.0893C2.5271 10.5743 0.7788 12.9055 1.0224 15.4724C1.266 18.0393 3.4216 20 6 20Z");
  stroke: none;
}

</style>
