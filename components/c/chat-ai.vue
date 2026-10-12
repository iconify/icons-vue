<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cp_rqybvs"/><path class="rgg9h4h5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-ai" /></template>
<style>
.cp_rqybvs {
  d: path("M12 3.25c5.1 0 9.25 3.6 9.25 8.25S17.1 19.75 12 19.75c-1.2 0-2.35-.2-3.4-.55l-4.25 1.6a.5.5 0 0 1-.65-.62l1.15-3.6c-1.25-1.38-2.1-3.13-2.1-5.08c0-4.65 4.15-8.25 9.25-8.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rgg9h4h5j {
  d: path("M12 7.25q.51 3.74 4.25 4.25q-3.74.51-4.25 4.25q-.51-3.74-4.25-4.25q3.74-.51 4.25-4.25");
}

</style>
