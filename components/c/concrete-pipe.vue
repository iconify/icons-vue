<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nv-mrbc3l"/><path class="ln8ikbc0w"/><path class="cnw92exdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:concrete-pipe" /></template>
<style>
.cnw92exdi {
  d: path("M5.75 11a1.25 4 0 1 0 2.5 0a1.25 4 0 1 0-2.5 0ZM2.5 20.75h19");
}

.ln8ikbc0w {
  d: path("M3 11a4 7 0 1 0 8 0a4 7 0 1 0-8 0Z");
}

.nv-mrbc3l {
  d: path("M7 4h10a4 7 0 0 1 0 14H7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
