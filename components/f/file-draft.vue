<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it-qfxbvy"/><path class="d7wx-9q1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-draft" /></template>
<style>
.d7wx-9q1e {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 4h4m2 9l.5-2.25L19 14.75a1.25 1.25 0 0 1 1.75 1.75l-4.25 4.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it-qfxbvy {
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3.5");
}

</style>
