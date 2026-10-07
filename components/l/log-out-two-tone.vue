<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n4ix3h0wp"/><path class="wsxgnbb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:log-out-two-tone" /></template>
<style>
.n4ix3h0wp {
  stroke-opacity: 0.4;
  d: path("M9 4L7 4C4.7909 4 3 5.7909 3 8L3 16C3 18.2091 4.7909 20 7 20L9 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wsxgnbb1d {
  d: path("M20.2307 12L10.1093 12M15.17 6.5L20.8359 11.6314C21.0547 11.8296 21.0547 12.1704 20.8359 12.3686L15.17 17.5");
}

</style>
