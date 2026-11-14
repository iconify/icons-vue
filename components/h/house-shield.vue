<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rtcz9xxhi"/><path class="rd2demb6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-shield" /></template>
<style>
.rd2demb6e {
  d: path("M8 20.5v-5h4v5m6.25-6.5l3.25 1.25V18c0 1.9-1.4 3.1-3.25 4c-1.85-.9-3.25-2.1-3.25-4v-2.75Z");
}

.rtcz9xxhi {
  d: path("M12.672 20.5H2.5v-10L11 3l8.5 7.5v1.028");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
