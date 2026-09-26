<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zmd9l0bgr"/><path class="a4r-1bbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-zap-fill" /></template>
<style>
.a4r-1bbra {
  d: path("M20 2L17 5L21 5L18 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zmd9l0bgr {
  fill: currentColor;
  d: path("M22 12L22 20.0002C21.9999 21.657 20.6568 23.0002 19 23.0002L16 23.0002L16 14.0002L8 14.0002L8 23.0002L5 23.0002C3.3432 23.0002 2.0001 21.657 2 20.0002L2 11.927C2 11.0454 2.3878 10.2079 3.0605 9.6379L10.0605 3.7073C11.0406 2.877 12.4212 2.7739 13.5007 3.3981C13.8098 3.5768 14 3.907 14 4.264L14 8C14 9.6569 15.3431 11 17 11L21 11C21.5523 11 22 11.4477 22 12Z");
  stroke: none;
}

</style>
