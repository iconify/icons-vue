<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f1qlx39yw"/><path class="b935atbpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-combo-duocolor-sharp" /></template>
<style>
.b935atbpy {
  d: path("M7 16v4m6-6v6m6-8v8M3 4v16h18");
}

.f1qlx39yw {
  stroke-opacity: 0.4;
  d: path("m3 11l6-6l6 4l6-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
