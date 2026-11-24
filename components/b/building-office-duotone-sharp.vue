<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t49rd7b1x"/><path class="dfddar9tv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office-duotone-sharp" /></template>
<style>
.dfddar9tv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21V5h16v16M3 21h18M8 9v4m4-4v4m4-4v4m-6 8v-4h4v4");
}

.ft5dv1b6b {
  fill: none;
}

.t49rd7b1x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 5h16v16H4Z");
}

</style>
