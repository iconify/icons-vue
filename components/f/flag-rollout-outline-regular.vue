<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="kow2ilbqy"/><path class="zos4srk3e"/><path class="y40ry_bij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flag-rollout-outline-regular" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.kow2ilbqy {
  d: path("M8 10v3");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y40ry_bij {
  d: path("M14 6v7");
}

.zos4srk3e {
  d: path("M11 8v5");
}

</style>
