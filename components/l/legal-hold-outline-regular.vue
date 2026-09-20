<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="k6od16bab"/><path class="st-dlsdww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:legal-hold-outline-regular" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.k6od16bab {
  d: path("M10 8v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.st-dlsdww {
  d: path("M14 8v8");
}

</style>
