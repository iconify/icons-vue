<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qixyd7blu"/><path class="im0v54a-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cow-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.im0v54a-o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6c3-1 7-1 10 0c.5 1 1 2 1 3c1-.5 2.5 0 3 1c-1 1-2 2-3 2c.5 1 1 2.5 1 5s-2 4-7 4s-7-1.5-7-4s.5-4 1-5c-1 0-2-1-3-2c.5-1 2-1.5 3-1c0-1 .5-2 1-3m0 0c-2.5-.5-4-1.5-4-3m14 3c2.5-.5 4-1.5 4-3M5.298 14C8.6 13 15.4 13 18.702 14M9 10h.01M15 10h.01M10 17h.01M14 17h.01");
}

.qixyd7blu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 6c.461.921.999 1.945 1 3c1.006-.502 2.496-.005 3 1c-1 1-2 2-3 2c.772 1.544 1 3.291 1 5c0 2.5-2 4-7 4s-7-1.5-7-4c0-1.709.228-3.456 1-5c-1 0-2-1-3-2c.504-1.005 1.994-1.502 3-1c.001-1.055.539-2.079 1-3c3-1 7-1 10 0m-6.99 10H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
