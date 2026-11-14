<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zs7-ek-rv"/><path class="hjh6s70yf"/><path class="ptbz_dtnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-deletion" /></template>
<style>
.hjh6s70yf {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75l.262-.001m5.521-.858q.386-.14.713-.296");
}

.ptbz_dtnt {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m6 1l5 5m0-5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zs7-ek-rv {
  d: path("M12.251 21.249L12 21.25c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v6.555");
}

</style>
