<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="czv3n_bph"/><path class="gex8qw2xt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-bunk-fill" /></template>
<style>
.czv3n_bph {
  d: path("M3 3V5M3 5V7V9M3 5H7C8.1046 5 9 5.8954 9 7V9M3 9V13M3 9H9M3 13V15V17M3 13H7C8.1046 13 9 13.8954 9 15V17M3 17V21M3 17H9M9 9H16M16 9H21M16 9V13M21 9V5V3M21 9V13M9 17H16M16 17H21M16 17V13M16 17V20V21M21 17V13M21 17V21M16 13H21");
}

.gex8qw2xt {
  fill: currentColor;
  d: path("M6 10L9 10C9.5523 10 10 9.5523 10 9L10 7C10 5.3431 8.6569 4 7 4L3 4C2.4477 4 2 4.4477 2 5L2 9C2 9.5523 2.4477 10 3 10ZM6 18L9 18C9.5523 18 10 17.5523 10 17L10 15C10 13.3431 8.6569 12 7 12L3 12C2.4477 12 2 12.4477 2 13L2 17C2 17.5523 2.4477 18 3 18Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
