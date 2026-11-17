<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d_rx15b9h"/><path class="l5ajbbt7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-moon-lightning-two-tone" /></template>
<style>
.d_rx15b9h {
  stroke-opacity: 0.4;
  d: path("M8.5 18.598C7.5718 18.062 7 17.072 7 16C7 14.343 8.3431 13 10 13C10 10.515 12.0147 8.5 14.5 8.5C16.9853 8.5 19 10.515 19 13C20.6569 13 22 14.343 22 16C22 17.072 21.4282 18.062 20.5 18.598");
}

.l5ajbbt7k {
  d: path("M3.7192 12.904C2.6137 11.704 2 10.132 2 8.5C2 4.91 4.9101 2 8.5 2C7.844 2.82 7.4866 3.839 7.4866 4.889C7.4866 5.747 7.7253 6.588 8.1761 7.318M15.5 17.5L13.25 20H16.25L14 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
