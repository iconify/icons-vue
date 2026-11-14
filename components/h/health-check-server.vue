<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bb97-f1ae"/><path class="fkcg0w6by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-check-server" /></template>
<style>
.bb97-f1ae {
  d: path("M13.8 15H2.5V3h17v10.3M17.8 15h-2.1");
}

.fkcg0w6by {
  d: path("M5.5 9H8l1.5-3l2 6L13 9h3m-1.25 9l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
