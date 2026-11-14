<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7n9s3x1x"/><path class="omapglbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-signature" /></template>
<style>
.omapglbyx {
  d: path("M5 13.5c1-3 2.25-3 2.75-1s1.75 2 2.5 0S12 11 13 13.25m1.75 8.5L15.5 19l4.25-4.25L22 17l-4.25 4.25ZM15.5 19l2.25 2.25M18.5 16l2.25 2.25");
}

.t7n9s3x1x {
  d: path("M12.6 18H2.5V7h13v8.1M2.5 7L6 3.5h13L15.5 7M19 3.5v8.1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
