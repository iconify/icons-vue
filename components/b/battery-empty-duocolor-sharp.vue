<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nmg30hbye"/><path class="q2xj2obyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-empty-duocolor-sharp" /></template>
<style>
.nmg30hbye {
  stroke-opacity: 0.4;
  d: path("M21 10v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q2xj2obyu {
  d: path("M3 7h15v10H3Z");
}

</style>
