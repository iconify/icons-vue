<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="e8lb8uc3g"/><path class="l12_cmb5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-offset-bottom-two-tone" /></template>
<style>
.e8lb8uc3g {
  stroke-opacity: 0.4;
  d: path("M4 12L22 12M2 20L14 20");
}

.l12_cmb5r {
  d: path("M16 4L22 4");
}

.to0c2ub7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
