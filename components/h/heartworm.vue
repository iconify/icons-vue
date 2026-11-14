<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t552xkpss"/><path class="cw1qlzhgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heartworm" /></template>
<style>
.cw1qlzhgv {
  d: path("M2.5 14q3-4.5 6-1.5t6 0t7-1.5");
}

.t552xkpss {
  d: path("M12 20c-6-4.5-9-7.5-9-11.5c0-3 2.25-5 4.75-5c2 0 3.25 1.25 4.25 2.75c1-1.5 2.25-2.75 4.25-2.75c2.5 0 4.75 2 4.75 5c0 4-3 7-9 11.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
