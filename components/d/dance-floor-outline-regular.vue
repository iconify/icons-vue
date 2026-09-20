<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="po47_2bjy"/><path class="oz614acod"/><path class="iqy6wdsji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dance-floor-outline-regular" /></template>
<style>
.iqy6wdsji {
  d: path("M8 16h7v5H8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oz614acod {
  d: path("M13 7h7v6h-7Z");
}

.po47_2bjy {
  d: path("M3 7h7v6H3Z");
}

</style>
