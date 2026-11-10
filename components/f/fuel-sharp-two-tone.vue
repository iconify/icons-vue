<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nqk1x9b4p"/><path class="a3aj0db6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fuel-sharp-two-tone" /></template>
<style>
.a3aj0db6i {
  d: path("M3 21V3H14V21M3 21H14M3 21H1M14 21H16M14 11H18V16C18 17.1 18.895 18 20 18C21.105 18 22 17.1 22 16V8L17.6 4.7M6 9H11");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nqk1x9b4p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 2C14.552 2 15 2.45 15 3V10H18C18.552 10 19 10.45 19 11V16C19 16.55 19.448 17 20 17C20.552 17 21 16.55 21 16V8.5L17 5.5L18.2 3.9L22.6 7.2C22.851 7.39 23 7.69 23 8V16C23 17.66 21.657 19 20 19C18.343 19 17 17.66 17 16V12H15V20H16V22H1V20H2V3C2 2.45 2.448 2 3 2H14Z");
  stroke: none;
}

</style>
