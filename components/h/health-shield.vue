<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_zvs3q8k"/><path class="ulske_0bk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-shield" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ulske_0bk {
  d: path("M6.5 12H9l1.25-3l2 6l1.5-3h3.75");
}

.x_zvs3q8k {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.75-7.5 10.5C8 19.75 4.5 16 4.5 11V5.5Z");
}

</style>
