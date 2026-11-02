<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g3_5jacow"/><path class="he86_fbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-off-duocolor-sharp" /></template>
<style>
.g3_5jacow {
  stroke-opacity: 0.4;
  d: path("m3 6l2-2m13-1l3 3M3 2l19 19");
}

.he86_fbbm {
  d: path("M7 6c-2.074 1.445-3 4.28-3 7a8 8 0 0 0 8 8c2.72 0 5.555-.926 7-3m1-5a8 8 0 0 0-8-8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
