<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e-667db3o"/><path class="d4vocib6k"/><path class="pmf__vb6m"/><path class="wj1odio5f"/><path class="z37iwiaad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cosmetic-linear" /></template>
<style>
.d4vocib6k {
  stroke-linejoin: round;
  d: path("M16.5 20V16M16.5 20H19.5M16.5 20H13.5");
}

.e-667db3o {
  d: path("M16.5 16C13.4624 16 11 13.5376 11 10.5C11 7.46243 13.4624 5 16.5 5C19.5376 5 22 7.46243 22 10.5C22 13.5376 19.5376 16 16.5 16Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pmf__vb6m {
  d: path("M3 11H7V5.61799C7 4.87461 6.21769 4.39111 5.55279 4.72356L3.55279 5.72356C3.214 5.89295 3 6.23922 3 6.61799V11Z");
}

.wj1odio5f {
  d: path("M8 11V17C8 18.6569 6.65685 20 5 20C3.34315 20 2 18.6569 2 17V11");
}

.z37iwiaad {
  d: path("M2 11H8");
}

</style>
