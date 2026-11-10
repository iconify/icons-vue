<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dduxf4bri"/><path class="xnlljt22s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-zap-two-tone" /></template>
<style>
.dduxf4bri {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 2C9.4846 2 10.8273 2.46 11.999 3.25C12.5188 2.9 13.0744 2.61 13.6641 2.4C13.9703 2.29 14.3104 2.34 14.5762 2.53C14.8419 2.71 15 3.02 15 3.34V9C15 10.66 16.3431 12 18 12H20.6143C20.9823 12 21.3208 12.2 21.4951 12.53C21.6694 12.85 21.6513 13.24 21.4482 13.55C20.415 15.11 18.9614 16.52 17.4209 17.83C16.6471 18.5 15.8359 19.15 15.0322 19.8C14.2244 20.45 13.4232 21.1 12.6494 21.76C12.2754 22.08 11.7246 22.08 11.3506 21.76C9.1622 19.89 6.5418 17.98 4.5781 15.99C2.582 13.97 1 11.64 1 8.75C1 4.98 4.1744 2 8 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xnlljt22s {
  d: path("M14 3.34C13.2837 3.6 12.6156 3.99 12 4.5C10.8426 3.55 9.5 3 8 3C4.6862 3 2 5.57 2 8.75C2 13.75 7.4376 17.1 12 21C15.1446 18.31 18.705 15.89 20.6141 13M21 3L18 6H22L19 9");
}

</style>
