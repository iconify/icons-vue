<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_vqhrbta"/><path class="psk23pi3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-right-2-two-tone" /></template>
<style>
.n_vqhrbta {
  stroke-opacity: 0.4;
  d: path("M16 4.5L3 4.5M16 9.5L3 9.5M16 14.5L6 14.5M16 19.5L10 19.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.psk23pi3k {
  d: path("M21 3L21 21");
}

</style>
