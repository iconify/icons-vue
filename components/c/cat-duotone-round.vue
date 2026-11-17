<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pmdn7mbrp"/><path class="eiqq58bsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cat-duotone-round" /></template>
<style>
.eiqq58bsm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20c-2 0-3.7-1.2-5-3c-.6-.8-1-2.5-1-4c0-2.5-1-4-1-6s0-4 1-4s2 2 4 4h4c2-2 3-4 4-4s1 2 1 4s-1 3.5-1 6c0 1.5-.4 3.2-1 4c-1.3 1.8-3 3-5 3m-9-7l5 1m-5 4l4-1m14-4l-5 1m5 4l-4-1m-8-6h.01M15 11h.01M11 14h2l-1 1Z");
}

.ft5dv1b6b {
  fill: none;
}

.pmdn7mbrp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 7h4c2-2 3-4 4-4s1 2 1 4s-1 3.5-1 6c0 1.5-.4 3.2-1 4c-1.19 1.646-2.879 2.999-5 3c-2.121-.001-3.81-1.354-5-3c-.6-.8-1-2.5-1-4c0-2.5-1-4-1-6s0-4 1-4s2 2 4 4");
}

</style>
