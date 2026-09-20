<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-eaarbln"/><path class="d85_p7ook"/><path class="y5eq5wale"/><path class="m_wupbc4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-interpreter-duotone-thin" /></template>
<style>
.d85_p7ook {
  d: path("m7 7 -5 5 5 5");
}

.g-eaarbln {
  fill: currentColor;
  d: path("M10 9v6l3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_wupbc4b {
  d: path("m17 7 5 5 -5 5");
}

.y5eq5wale {
  d: path("M10 9v6l3 -3Z");
}

</style>
