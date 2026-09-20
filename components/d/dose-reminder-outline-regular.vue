<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rruu58b-y"/><path class="u6dphkbyx"/><path class="k1uyapbnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dose-reminder-outline-regular" /></template>
<style>
.k1uyapbnn {
  d: path("M17 14v3h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rruu58b-y {
  d: path("m4 11 5 -5a3.5 3.5 0 0 1 5 5l-5 5a3.5 3.5 0 0 1 -5 -5");
}

.u6dphkbyx {
  d: path("M13 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
