<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k6yzp7t-z"/><path class="n1941ac-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-text-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k6yzp7t-z {
  stroke-opacity: 0.4;
  d: path("M2 3.5H13.9583M2 8.1006H6.9875M2 12.7011H6.9875");
}

.n1941ac-k {
  fill: currentColor;
  d: path("M9.31097 10.3752C8.96482 9.25452 10.0066 8.07664 11.2241 8.49437L11.2231 8.49535L20.9838 11.8411C22.2927 12.2898 22.3471 14.1241 21.0864 14.6633L17.1616 16.3401L15.2133 20.6194C14.6354 21.8879 12.8276 21.7484 12.4223 20.4377L9.31097 10.3752Z");
  stroke: none;
}

</style>
