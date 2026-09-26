<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tdi2d7lly"/><path class="jbg64mbay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bird-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jbg64mbay {
  fill: currentColor;
  d: path("M17 8C17 8.5523 16.5523 9 16 9C15.4477 9 15 8.5523 15 8C15 7.4477 15.4477 7 16 7C16.5523 7 17 7.4477 17 8Z");
  stroke: none;
}

.tdi2d7lly {
  d: path("M10.8703 7.0963L2 19.3162C4.3886 18.9914 6.7693 18.5988 8.1714 17.8575C19.009 18.1077 21.551 8.4795 19.2462 5.3327C16.6431 1.63 13.9428 3.1503 12.918 4.3733L10.8703 7.0963ZM8.1714 17.8575C13.4666 15.0578 12.4764 9.9085 10.8703 7.0963M20.0269 7.2419L22 9.0783L20.0269 10.1M10 17.9861L10 22M13.5 17.4L13.5 20.9714");
}

</style>
