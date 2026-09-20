<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nt8cxnbeh"/><path class="y7_y8yq8z"/><path class="qvx0fvm9m"/><path class="m2ri9cc6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-center-horizontal-outline-regular" /></template>
<style>
.m2ri9cc6o {
  d: path("M14 9.5h4v5h-4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nt8cxnbeh {
  d: path("M3 12h2.5");
}

.qvx0fvm9m {
  d: path("M7 8h4v8H7Z");
}

.y7_y8yq8z {
  d: path("M18.5 12H21");
}

</style>
