<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ri0p6tz1n"/><path class="q03s1s14v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-alert" /></template>
<style>
.q03s1s14v {
  d: path("M18.5 15.5q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3Z");
}

.ri0p6tz1n {
  d: path("M15.458 19H3l9-16l7.011 12.464M12 9v4m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
