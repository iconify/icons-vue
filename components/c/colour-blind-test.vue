<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iawfys5wp"/><path class="exih_lbub"/><path class="g_3i87pkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-blind-test" /></template>
<style>
.exih_lbub {
  d: path("M7.5 10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm6.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.g_3i87pkq {
  fill: currentColor;
  d: path("M18 14.25a3.75 3.75 0 0 0 0 7.5Z");
}

.iawfys5wp {
  d: path("M2.5 10C5 5.5 14 5.5 17 10c-3 4.5-12 4.5-14.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
