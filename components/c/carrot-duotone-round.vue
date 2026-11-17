<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q0rrr99jp"/><path class="zmtsjs1io"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:carrot-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q0rrr99jp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 3c1.915.615 2.119 2.841.104 4.896C18.159 5.881 20.385 6.085 21 8c-.606 1.889-2.779 2.113-4.81.187A4.3 4.3 0 0 1 15 15L3 21L9 9a4.302 4.302 0 0 1 6.813-1.19C13.887 5.779 14.111 3.606 16 3");
}

.zmtsjs1io {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21L9 9c1.343-2.687 4.958-3.203 7-1c2.203 2.042 1.687 5.657-1 7Zm5-10l2 1m1 5l-2-1m7-13c-1.948.625-2.125 2.917 0 5c2.125-2.083 1.948-4.375 0-5m5 5c-.625 1.948-2.917 2.125-5 0c2.083-2.125 4.375-1.948 5 0m-5 0h.01");
}

</style>
