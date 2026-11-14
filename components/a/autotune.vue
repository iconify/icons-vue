<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ghqq34bih"/><path class="uzc1k5bdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:autotune" /></template>
<style>
.ghqq34bih {
  d: path("M3 2.5V21h18.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzc1k5bdu {
  d: path("M6 13c1.5-6 4-6 5.5-1c.75 2.5 1.5 3 2.5 3h2.5V8h5");
}

</style>
