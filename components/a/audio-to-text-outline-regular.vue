<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="lib1k_nwv"/><path class="fdjxfnx9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-to-text-outline-regular" /></template>
<style>
.fdjxfnx9f {
  d: path("M13 10.5h5");
}

.jq9hovbrs {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.lib1k_nwv {
  d: path("M6 10.5 8.5 8l2.5 2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yomctlb4k {
  d: path("M7 17v4l4 -4");
}

</style>
