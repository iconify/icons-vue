<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="owy_gbbrp"/><path class="koav1eb-y"/><path class="flc_k6b4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loan-working-capital" /></template>
<style>
.flc_k6b4r {
  d: path("m15.5 14.5l.25 1.5l1.5.25");
}

.koav1eb-y {
  d: path("M20.121 15.879a3 3 0 1 1-4.242 0");
}

.owy_gbbrp {
  d: path("M12.5 20h-10V7h19v6.3M8.5 7V5.5A1.5 1.5 0 0 1 10 4h4a1.5 1.5 0 0 1 1.5 1.5V7m-13 5.5h9.8m5.7 0h1.6m1.1 0h.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
