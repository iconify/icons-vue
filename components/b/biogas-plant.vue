<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mkif7cbgv"/><path class="t0hlzeb7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biogas-plant" /></template>
<style>
.mkif7cbgv {
  d: path("M4 21.5V14a5 5 0 0 1 10 0v7.5Z");
}

.t0hlzeb7v {
  d: path("M13 11h4.5V9.75m0 0c-2 0-2.75-1.75-2-3.25c.25.75.75 1 1.25 1c-.5-1.75.25-3.25 1.5-4.25c.25 1.75 2 2.5 2 4.25c0 1.25-1 2.25-2.75 2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
