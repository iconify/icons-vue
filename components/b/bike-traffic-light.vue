<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tudp38ixb"/><path class="bjhwmehgg"/><path class="qe4h11bxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-traffic-light" /></template>
<style>
.bjhwmehgg {
  d: path("M6.25 6.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm0 5.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm0 5.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm8 2.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4.25 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.qe4h11bxa {
  d: path("m16 19.5l1.75-3.5h1.75l.75 3.5");
}

.tudp38ixb {
  d: path("M11.4 21.5H3.5v-19h8v14.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
