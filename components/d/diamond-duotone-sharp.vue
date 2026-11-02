<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kf9pqxb4y"/><path class="f9m6b1nqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-duotone-sharp" /></template>
<style>
.f9m6b1nqa {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 17l-5 5L2 12L12 2l10 10z");
}

.ft5dv1b6b {
  fill: none;
}

.kf9pqxb4y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17 17l-5 5L2 12L12 2l10 10Z");
}

</style>
