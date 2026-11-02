<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m7rv9fn4u"/><path class="auxv78bvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-to-go-duotone" /></template>
<style>
.auxv78bvd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7c-1 0-1.5-.2-1-1l1-2c.5-1 1-1 2-1h8c1 0 1.5 0 2 1l1 2c.5.8 0 1-1 1Zm0 0l1 12c.1 1.2.8 2 2 2h6c1.2 0 1.9-.8 2-2l1-12M7 12h10M7 16h10");
}

.ft5dv1b6b {
  fill: none;
}

.m7rv9fn4u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m4.125 5.514l.981-1.961c.468-.937 1.09-1.449 2.15-1.534C7.503 1.999 7.752 2 8 2h8c.248 0 .497-.001.744.019c1.06.085 1.682.597 2.15 1.534l.981 1.961c.168.279.299.592.319.92c.026.443-.16.87-.507 1.147c-.248.199-.557.306-.867.36c-.27.047-.546.059-.82.059H6c-.577 0-1.218-.044-1.687-.419a1.36 1.36 0 0 1-.507-1.147c.02-.328.151-.641.319-.92M17 11a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Z");
}

</style>
