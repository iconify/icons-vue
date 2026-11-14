<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n41gagbod"/><path class="pa6efk4gu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:altitude-sickness" /></template>
<style>
.n41gagbod {
  d: path("m2.5 19.5l7.5-16l4 7.5l2-2.5l3.202 3.202m1.555 1.555L21.5 14");
}

.pa6efk4gu {
  d: path("m7.75 8.25l2.25 2l2.5-2M18 14.5V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
