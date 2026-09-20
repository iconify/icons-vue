<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h-ljjxb1p"/><path class="izmrq5b4m"/><path class="eeoxujb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keep-left-outline-regular" /></template>
<style>
.eeoxujb4a {
  d: path("m14 11 5 -5");
}

.h-ljjxb1p {
  d: path("M12 22v-9L5 6");
}

.izmrq5b4m {
  d: path("M5 10.5V6h4.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
