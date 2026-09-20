<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="geztznlon"/><path class="f0k-qn7fa"/><path class="zicuro7zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dress-code-outline-regular" /></template>
<style>
.f0k-qn7fa {
  d: path("m20 7 -4 4 4 4Z");
}

.geztznlon {
  d: path("m4 7 4 4 -4 4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zicuro7zb {
  d: path("M10 8h4v6h-4Z");
}

</style>
