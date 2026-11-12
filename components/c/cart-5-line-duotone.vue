<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n86dheb3w"/><path class="cuytl5bgh"/><path class="wat-0tb8a"/><path class="jwuxyw18e"/><path class="p4wackbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-5-line-duotone" /></template>
<style>
.cuytl5bgh {
  stroke-linejoin: round;
  d: path("M8 12H16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwuxyw18e {
  stroke-linejoin: round;
  d: path("M18 9L15 3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n86dheb3w {
  d: path("M9.85004 21H14.1491C16.4732 21 17.6353 21 18.4603 20.333C19.2854 19.666 19.5289 18.5297 20.0159 16.2572L20.4444 14.2572C21.1629 10.9043 21.5221 9.22793 20.6216 8.11397C19.721 7 18.0066 7 14.5776 7H9.42147C5.99253 7 4.27806 7 3.37751 8.11397C2.47696 9.22793 2.83619 10.9043 3.55466 14.2572L3.98323 16.2572C4.4702 18.5297 4.71369 19.666 5.53876 20.333C6.36383 21 7.5259 21 9.85004 21Z");
}

.p4wackbxx {
  stroke-linejoin: round;
  d: path("M6 9L9 3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wat-0tb8a {
  stroke-linejoin: round;
  d: path("M10 15H14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
