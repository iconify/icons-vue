<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hhpuz9bck"/><path class="a0s4n_b3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask-duotone-round" /></template>
<style>
.a0s4n_b3v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3v6l-4 8c-.919 1.838.162 4 2 4h8c1.838 0 2.919-2.162 2-4l-4-8V3M8 3h8M7 15h10");
}

.ft5dv1b6b {
  fill: none;
}

.hhpuz9bck {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 14c.379 0 .725.214.894.553l1 2c.56 1.12.597 2.457.034 3.583a3.44 3.44 0 0 1-1.154 1.328A3.2 3.2 0 0 1 16 22H8a3.2 3.2 0 0 1-1.774-.536a3.44 3.44 0 0 1-1.154-1.328c-.563-1.126-.526-2.463.034-3.583l1-2A1 1 0 0 1 7 14Z");
}

</style>
