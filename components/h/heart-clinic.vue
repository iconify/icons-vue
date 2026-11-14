<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y9n1iym_q"/><path class="z1ea5gr1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-clinic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9n1iym_q {
  d: path("M5.125 7h13.75A2.625 2.625 0 0 1 21.5 9.625v9.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-9.25A2.625 2.625 0 0 1 5.125 7M2.5 7l2-3.5h15l2 3.5");
}

.z1ea5gr1k {
  d: path("M12 14.75S9.25 13 9.25 11.25c0-.75.75-1.5 1.5-1.5c.5 0 1 .5 1.25.75c.25-.25.75-.75 1.25-.75c.75 0 1.5.75 1.5 1.5c0 1.75-2.75 3.5-2.75 3.5m-2 6.75v-4h4v4");
}

</style>
