<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="trtifv9xg"/><path class="qxzs1jb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-upper-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qxzs1jb2e {
  d: path("M15.945 18.67L19.002 10L22.059 18.67M16.886 16H21.118");
}

.trtifv9xg {
  stroke-opacity: 0.4;
  d: path("M1.93 18.63L7.002 6L12.074 18.63M4.19 13H9.813");
}

</style>
