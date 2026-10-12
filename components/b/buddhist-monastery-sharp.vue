<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ihrnpzbbf"/><path class="llylxwbte"/><path class="r6ukerboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buddhist-monastery-sharp" /></template>
<style>
.ihrnpzbbf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.5h10.5l.39.31l2.97 2.38l.39.31H19v9.75H5V11.5H2.75l.39-.31l2.97-2.38l.39-.31zm-2 3h14");
}

.llylxwbte {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 15.25h.01m7.99 0h.01");
}

.r6ukerboa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25V17h3v4.25M9.25 8.5a2.75 2.75 0 0 1 5.5 0ZM12 5.75V3");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
