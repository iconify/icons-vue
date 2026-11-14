<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="os16wc5ob"/><path class="a7_nh6bhi"/><path class="q15aztb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-order" /></template>
<style>
.a7_nh6bhi {
  fill: currentColor;
  d: path("M11.735 16.815C11.204 18.084 9.938 19 8.5 19C6.6 19 5 17.4 5 15.5V11h7v4.2");
}

.os16wc5ob {
  d: path("M5 2.5v13C5 17.4 6.6 19 8.5 19c1.442 0 2.711-.921 3.239-2.196M12 15.189V2.5m-8.5 0h10");
}

.q15aztb6y {
  d: path("M18 14.5v7M14.5 18h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
