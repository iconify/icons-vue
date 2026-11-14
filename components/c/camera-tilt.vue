<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdshkub5i"/><path class="rbl_1pf8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-tilt" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rbl_1pf8k {
  d: path("M12.244 10.066L13 9.625a.997.997 0 0 1 1.5.862v3.026a.997.997 0 0 1-1.5.862l-.756-.441a1.5 1.5 0 0 1-.744-1.296v-1.276a1.5 1.5 0 0 1 .744-1.296M19.5 3.5v17m-2-15l2-2l2 2m-4 13l2 2l2-2");
}

.wdshkub5i {
  d: path("M6 7h2a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 8 17H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 7");
}

</style>
