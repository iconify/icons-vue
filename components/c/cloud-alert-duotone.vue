<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vevmidywk"/><path class="asqgg9bdm"/><path class="j_rl4l5tj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-alert-duotone" /></template>
<style>
.asqgg9bdm {
  d: path("M12 9L12 11");
}

.j_rl4l5tj {
  fill: currentColor;
  d: path("M13 15C13 15.5523 12.5523 16 12 16C11.4477 16 11 15.5523 11 15C11 14.4477 11.4477 14 12 14C12.5523 14 13 14.4477 13 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vevmidywk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 20L18 20C20.5784 20 22.734 18.0393 22.9776 15.4724C23.2212 12.9055 21.4729 10.5743 18.9405 10.0893C18.4833 6.6052 15.5139 4 12 4C8.4861 4 5.5167 6.6052 5.0595 10.0893C2.5271 10.5743 0.7788 12.9055 1.0224 15.4724C1.266 18.0393 3.4216 20 6 20Z");
  stroke: none;
}

</style>
