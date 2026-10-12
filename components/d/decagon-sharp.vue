<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uap_-ibwu"/><path class="ee_4racht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:decagon-sharp" /></template>
<style>
.ee_4racht {
  d: path("M7.75 9.5L9.5 8.25v7.5m4.75-7.5c1.25 0 2 1.5 2 3.75s-.75 3.75-2 3.75s-2-1.5-2-3.75s.75-3.75 2-3.75Z");
}

.uap_-ibwu {
  d: path("m21.05 12.48l-1.45 4.45l-.16.48l-.4.29l-3.79 2.76l-.41.29H9.16l-.41-.29l-3.79-2.76l-.4-.29l-.16-.48l-1.45-4.45L2.8 12l.15-.48L4.4 7.07l.16-.48l.4-.29l3.79-2.76l.41-.29h5.68l.41.29l3.79 2.76l.4.29l.16.48l1.45 4.45l.15.48z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
