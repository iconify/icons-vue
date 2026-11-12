<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cza3bv7wt"/><path class="ap87rxbvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-duotone" /></template>
<style>
.ap87rxbvt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17C1.262 12.302 4.584 3 12 3s10.738 9.302 5 14M5 18a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm4-8a3 3 0 0 1 3-3");
}

.cza3bv7wt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.071 16.31c.573.364.929 1.011.929 1.69v2c0 1.1-.9 2-2 2H6c-1.1 0-2-.9-2-2v-2c0-.679.356-1.326.929-1.69a8.68 8.68 0 0 1-1.823-5.862a9.2 9.2 0 0 1 1.731-4.845A8.7 8.7 0 0 1 9.104 2.46a9.28 9.28 0 0 1 5.792 0c.868.29 1.687.718 2.42 1.266a9 9 0 0 1 3.059 4.176c1.02 2.858.572 6.008-1.304 8.408");
}

.ft5dv1b6b {
  fill: none;
}

</style>
